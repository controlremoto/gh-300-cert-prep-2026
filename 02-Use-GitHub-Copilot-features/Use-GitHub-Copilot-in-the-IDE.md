# Use GitHub Copilot in the IDE

## Learning Points

### Enable Copilot in the IDE

| Step                | Description                                                      |
| :------------------ | :-------------------------------------------------------------- |
| Install Extension   | Add the GitHub Copilot extension to your IDE (e.g., VS Code).   |
| Sign In             | Authenticate with your GitHub account (Copilot subscription required). |
| Enable Copilot      | Activate Copilot in the IDE settings or command palette.         |

**Exam Tricky Points:**
- Copilot must be enabled per user and per IDE instance.
- Some features may require additional permissions or organization policies.

---

### Trigger Copilot through Inline Suggestions, Chat, CLI, and Plan Mode

| Feature           | How to Trigger / Use                                             |
| :---------------- | :-------------------------------------------------------------- |
| Inline Suggestions| Start typing code; Copilot offers suggestions automatically.     |
| Copilot Chat      | Open the Copilot Chat panel or use the command palette.          |
| Copilot CLI       | Use the Copilot CLI in the terminal for code generation tasks.   |
| Plan Mode         | Use Plan Mode to generate multi-step plans for complex tasks.    |

**Exam Tricky Points:**
- Inline suggestions are context-aware and may differ based on file content.
- Plan Mode is available only in supported IDEs and may require preview features.

---


### Exclude Specific Files or Repositories (App Knowledge)

| Method                  | Description                                               |
| :---------------------- | :------------------------------------------------------- |
| Editor Settings         | Limit Copilot by language or file type in IDE settings (e.g., VS Code `settings.json`). |
| Repository/Org/Enterprise Settings | Configure content exclusions in GitHub repository, organization, or enterprise settings. |

**Exam Tricky Points:**
- Content exclusions are managed through GitHub settings, not via a `.copilotignore` file.
- Exclusion patterns use fnmatch-style syntax and are entered in the GitHub UI (not in the repo itself).
- Exclusions may take up to 30 minutes to propagate to IDEs.

**Official documentation:**
- [Excluding content from GitHub Copilot](https://docs.github.com/en/copilot/how-tos/configure-content-exclusion/exclude-content-from-copilot)


---

## Interactive Flashcards

<details>
<summary><strong>❓ Question:</strong> How do you enable GitHub Copilot in VS Code?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>Install the GitHub Copilot extension, sign in with your GitHub account, and enable Copilot in the IDE settings.
</details>

<details>
<summary><strong>❓ Question:</strong> How do you exclude specific files or folders from Copilot suggestions?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>By configuring content exclusions in your repository, organization, or enterprise settings on GitHub.com using path patterns.
</details>

<details>
<summary><strong>❓ Question:</strong> How can you trigger Copilot Chat in the IDE?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>Open the Copilot Chat panel or use the command palette to start a chat session.
</details>
