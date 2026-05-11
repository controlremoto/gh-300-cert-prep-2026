# Manage Organization-Wide Settings and Policies

## Learning Points

### Configure Organization-Wide Policy Management

| Policy Area                | Description                                                      |
| :------------------------- | :-------------------------------------------------------------- |
| Feature Availability       | Control which Copilot features are enabled for all users/IDEs.   |
| Code Review Policies       | Enforce Copilot Code Review standards across the organization.   |
| Centralized Management     | Apply consistent settings via GitHub organization admin.         |

**Exam Tricky Points:**
- Organization policies override individual user settings.
- Some features require enterprise or team plans.

---

### Enable Copilot Code Review Policies and Manage Feature Availability

| Task                      | How to Perform                                                   |
| :------------------------ | :-------------------------------------------------------------- |
| Enable Code Review        | Set policies in organization settings on GitHub.com.             |
| Manage IDE Features       | Use admin controls to enable/disable Copilot features per IDE.   |

**Exam Tricky Points:**
- Code review policies can enforce standards for all repositories.
- Feature availability can be restricted to specific teams or projects.

---

### Utilize Audit Log Events

| Event Type                | Description                                                      |
| :------------------------ | :-------------------------------------------------------------- |
| Copilot Usage             | Track when and how Copilot is used across the organization.      |
| Policy Changes            | Log changes to Copilot-related settings and policies.            |

**Exam Tricky Points:**
- Audit logs help with compliance and troubleshooting.
- Only organization admins can access full audit logs.

---

### Manage Subscriptions Using the REST API

| Action                    | How to Perform                                                   |
| :------------------------ | :-------------------------------------------------------------- |
| View Subscriptions        | Use the GitHub REST API to list Copilot subscriptions.           |
| Update Subscriptions      | Modify or assign subscriptions via API endpoints.                |

**Exam Tricky Points:**
- API access may require specific scopes or tokens.
- Subscription changes via API are logged for auditing.

---

## Interactive Flashcards

<details>
<summary><strong>❓ Question:</strong> Who can configure organization-wide Copilot policies?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>Only organization administrators can configure and enforce Copilot policies for all users.
</details>

<details>
<summary><strong>❓ Question:</strong> What is the purpose of Copilot audit log events?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>They track Copilot usage and policy changes for compliance and troubleshooting.
</details>

<details>
<summary><strong>❓ Question:</strong> How can subscriptions be managed programmatically?</summary>
<strong>🙋🏻‍♂️ Answer: </strong>By using the GitHub REST API to view, assign, or update Copilot subscriptions.
</details>
