---
name: assessment-questions-formatter
description: Convert any raw markdown file into a formatted markdown document matching the style of `practice-assessment-for-GH-300.md`. Use when user ask to format the document with assessment formatting.
---

# Assessment Question Formatter

## Purpose
Convert any raw markdown file into a formatted markdown document matching the style of `practice-assessment-for-GH-300.md`. This includes:
- Numbered questions with lettered options
- Answers hidden in expandable `<details>` blocks
- Consistent headings, spacing, and bullet formatting

## Workflow
1. **Parse Input**: Identify numbered questions, answer options, and answer explanations.
2. **Normalize Structure**:
    - Ensure each question starts with a number and period (e.g., `1.`)
    - Each answer option starts with `- (A)`, `- (B)`, etc.
    - Remove extra blank lines (max 1 between blocks)
3. **Convert Answers**:
    - For each question, wrap the answer and explanation in a `<details>` block.
    - Use `<summary><strong>Check your answer:</strong></summary>` for the summary line.
    - Start the answer with `<strong>{LETTER} — {SHORT}</strong><br>`
    - Place the explanation below, separated by `<br>` if needed.
4. **Preserve Code Blocks & Tables**: Do not alter fenced code blocks or markdown tables.
5. **Validate Output**: Render in Markdown preview to ensure all `<details>` expand and formatting matches the example.

## Patterns & Regex
- **Question**: `^\d+\.`
- **Option**: `^- \([A-Z]\) `
- **Answer Block**: Look for lines after options, or explicit `Answer:`/`Explanation:` markers.
- **Details Block**: Wrap answer/explanation as:
  ```html
  <details>
  <summary><strong>Check your answer:</strong></summary>
  <strong>B — Correct answer short text</strong><br>
  Explanation text here.
  </details>
  ```
- **Spacing**: Collapse multiple blank lines to one. Ensure single trailing newline.

## Example Conversion
### Raw Input
```
1. What is the purpose of code refactoring?
To alter the external behavior
To improve the internal structure
To add new features
To optimize performance

Answer: B — Refactoring enhances the internal structure while maintaining the same external behavior.
Explanation: Refactoring improves readability, maintainability, and design without changing external behavior.
```

### Converted Output
```
1. What is the purpose of code refactoring?
- (A) To alter the external behavior
- (B) To improve the internal structure
- (C) To add new features
- (D) To optimize performance

<details>
<summary><strong>Check your answer:</strong></summary>
<strong>B — Refactoring enhances the internal structure while maintaining the same external behavior.</strong><br>
Refactoring improves readability, maintainability, and design without changing external behavior.
</details>
```

## Testing Checklist
- [ ] All questions are numbered and options are lettered
- [ ] Each answer is in a `<details>` block with summary
- [ ] No more than one blank line between blocks
- [ ] Code blocks and tables are preserved
- [ ] Preview renders as expected in VS Code

## Edge Cases
- Multi-line options: Indent continuation lines
- Nested lists: Preserve indentation
- Answers referencing code: Place code blocks outside `<details>`

## Automation Hints
- Use regex or markdown parser to split questions and options
- Insert `<details>` after options, before next question or end of file
- Optionally inject YAML frontmatter if metadata is needed

---
**Example prompt:**
> Format this raw markdown file as an exam-style Q/A document using the SKILL.md rules.
