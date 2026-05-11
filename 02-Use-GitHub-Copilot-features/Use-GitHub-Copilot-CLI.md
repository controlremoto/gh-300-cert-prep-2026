# Use GitHub Copilot CLI

## Learning Points

### Define GitHub Copilot CLI and How It Benefits Developers

| Feature                | Benefit                                                      |
| :--------------------- | :---------------------------------------------------------- |
| Natural Language to CLI| Converts plain language prompts into shell commands/scripts. |
| Automation             | Automates repetitive tasks and script generation.            |
| Productivity           | Reduces manual coding and context switching.                 |

**Exam Tricky Points:**
- Copilot CLI is separate from the IDE extension and must be installed independently.
- Requires authentication with a GitHub account that has a Copilot subscription.

---

### Identify the Steps for Installing GitHub Copilot CLI

| Step                | Description                                                      |
| :------------------ | :-------------------------------------------------------------- |
| Prerequisites       | Ensure Node.js and npm are installed.                            |
| Install Package     | Run `npm install -g @githubnext/github-copilot-cli`.             |
| Authenticate        | Run `gh auth login` and `copilot auth login` as needed.          |

**Exam Tricky Points:**
- Installation may require admin privileges.
- Authentication is required for full CLI functionality.

---


### Describe Key GitHub Copilot CLI Features and Commands

| Command/Feature     | Description                                                      | Example & Expected Output |
| :------------------ | :-------------------------------------------------------------- | :----------------------- |
| `copilot suggest`   | Generates shell commands/scripts from natural language prompts.  | `copilot suggest "list all .txt files"` → `ls *.txt` |
| `copilot explain`   | Explains what a shell command or script does.                    | `copilot explain "rm -rf /tmp/*"` → "Deletes all files and folders in /tmp directory." |
| `copilot fix` | Suggests fixes for errors in scripts or commands. | `copilot fix "ls -l \| grpe txt"` → Suggests: `ls -l \| grep txt` |
| Interactive Mode    | Allows ongoing sessions for multiple prompts.                    | `copilot interactive` → (Session starts, multiple prompts accepted) |

**Exam Tricky Points:**
- Not all shell environments are supported equally.
- Some features may be in preview or require updates.

---


### Use GitHub Copilot CLI Interactively and in Sessions

| Mode                | Description                                                      | Example & Expected Output |
| :------------------ | :-------------------------------------------------------------- | :----------------------- |
| Interactive         | Start a session to ask multiple questions or generate scripts.   | `copilot interactive` → (Prompt: `How do I find all .md files?` → `find . -name "*.md"`) |
| One-off             | Run single commands for quick suggestions or explanations.       | `copilot suggest "show disk usage"` → `du -h` |

**Exam Tricky Points:**
- Interactive sessions maintain context between prompts.
- Exiting a session returns to the normal shell prompt.

---


### Generate Scripts and Manage Files with GitHub Copilot CLI

| Task                | How Copilot CLI Helps                                            | Example & Expected Output |
| :------------------ | :-------------------------------------------------------------- | :----------------------- |
| Script Generation   | Quickly creates scripts for automation or setup tasks.           | `copilot suggest "backup home directory to /backup"` → `cp -r ~/ /backup/` |
| File Management     | Suggests commands for file operations (move, copy, delete, etc). | `copilot suggest "move all log files to archive"` → `mv *.log archive/` |

**Exam Tricky Points:**
- Always review generated scripts for accuracy and security.
- Copilot CLI does not execute commands automatically; user confirmation is required.

---

## Interactive Flashcards

<details>
<summary><strong>❓ Question:</strong> What is the main benefit of GitHub Copilot CLI?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>It converts natural language prompts into shell commands or scripts, automating tasks and boosting productivity.
</details>

<details>
<summary><strong>❓ Question:</strong> How do you install GitHub Copilot CLI?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>Install Node.js and npm, then run `npm install -g @githubnext/github-copilot-cli`.
</details>

<details>
<summary><strong>❓ Question:</strong> What does the `copilot explain` command do?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>It explains what a given shell command or script does in plain language.
</details>
