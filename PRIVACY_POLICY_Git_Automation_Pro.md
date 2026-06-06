# Privacy Policy for Git Automation Pro

**Last updated:** June 6, 2026

Git Automation Pro is a desktop application designed to help users perform common Git and GitHub operations through a graphical interface.

This Privacy Policy explains what information the application uses, how it is stored, and how it is protected.

## 1. Summary

Git Automation Pro is designed to work locally on the user's computer.

The application does **not** operate its own server, does **not** sell user data, does **not** display advertising, and does **not** intentionally collect analytics or telemetry.

Some information is required for the application to connect to GitHub and perform Git operations. This information is used only for the features requested by the user.

## 2. Information the Application May Use

Git Automation Pro may use the following types of information:

- GitHub authentication information, such as a Personal Access Token or OAuth access token.
- GitHub repository metadata, such as repository name, owner, default branch, visibility, clone URL, issues, and pull requests.
- Local workspace settings, such as the selected local repository path and default branch.
- User-entered Git data, such as commit messages, branch names, pull request titles, and pull request descriptions.
- Git command output, such as status, branch list, commit history, pull results, push results, and error messages.

## 3. GitHub Authentication

Git Automation Pro supports authentication using:

- Personal Access Token
- OAuth Device Flow, when configured by the user

Authentication tokens are used only to communicate with GitHub and to perform GitHub-related actions requested by the user.

The application is designed not to display, print, or log authentication tokens.

## 4. Token Storage

When token saving is enabled, Git Automation Pro stores authentication tokens using the operating system's secure credential storage through the `keyring` library, when available.

Depending on the operating system, this may use secure storage such as:

- Windows Credential Manager
- macOS Keychain
- Linux Secret Service or compatible keyring backend

If secure credential storage is unavailable, the application should notify the user instead of intentionally saving tokens in plain text.

## 5. Local Settings Storage

Git Automation Pro may store non-sensitive settings locally on the user's computer, including:

- Last selected repository
- Local workspace path
- Default branch
- Safe Mode setting
- Theme preference
- Auto Pull or Auto Push preferences, if enabled

These settings are stored locally and are used only to restore the user's preferred application configuration.

## 6. Repository and File Access

Git Automation Pro performs Git operations only on repositories and local paths selected by the user.

The application may read Git metadata and command output from the selected repository in order to show status, branch information, commit history, and operation results.

The application does not intentionally upload local files anywhere except when the user explicitly performs Git operations such as push, pull request creation, or other GitHub-related actions.

## 7. Logs

Git Automation Pro may show an activity log inside the application to help the user understand what operations were performed.

The application is designed to avoid logging sensitive information, including:

- Authentication tokens
- Passwords
- Full secret values
- Sensitive authorization headers

Logs may include operation names, Git command results, sanitized error messages, repository names, branch names, and general status messages.

Users should still review logs before sharing them publicly.

## 8. Network Communication

Git Automation Pro may communicate with GitHub services when the user performs actions such as:

- Testing GitHub authentication
- Loading repositories
- Reading issues
- Reading pull requests
- Creating pull requests
- Performing authenticated Git operations

The application communicates with GitHub using GitHub APIs and Git command-line operations.

Git Automation Pro does not intentionally send user data to any third-party service other than GitHub, unless the user configures the application or Git itself to do so.

## 9. Third-Party Services

Git Automation Pro relies on GitHub for repository hosting and GitHub account authentication.

Use of GitHub is subject to GitHub's own terms and privacy practices.

The application may also rely on locally installed Git and Python libraries required for its functionality.

## 10. Safe Mode and User Confirmation

Git Automation Pro includes Safe Mode features to help prevent accidental execution of sensitive operations.

Sensitive operations such as force push, branch deletion, reset, clean, or overwrite-style actions should require explicit confirmation before execution.

Users remain responsible for reviewing operations before approving them, especially when using workflows or automation features.

## 11. Automation Workflows

Git Automation Pro may allow users to create or run workflows such as:

- Pull, add, commit, and push
- Create branch, commit, push, and create pull request
- Sync repository
- Backup local changes
- Release preparation

Workflow data may be stored locally as application settings or configuration.

Before running workflows, users should review the preview or dry-run output where available.

## 12. Data Sharing

Git Automation Pro does not sell, rent, or trade user data.

The application does not intentionally share user data with third parties except as required to perform user-requested operations with GitHub.

## 13. Data Retention

Authentication tokens remain stored until the user removes them from the application or deletes them from the operating system credential store.

Local settings remain stored until the user resets the application settings, deletes the configuration files, or uninstalls the application depending on the operating system behavior.

Repository data remains in the user's local workspace and is controlled by the user.

## 14. User Control

Users can control their data by:

- Removing the saved token from the application or operating system credential manager.
- Revoking the GitHub token from GitHub account settings.
- Deleting local workspace folders.
- Clearing application logs.
- Resetting application settings.
- Removing repository access from the GitHub token or OAuth authorization.

## 15. Security Recommendations

Users are encouraged to:

- Use fine-grained GitHub tokens whenever possible.
- Grant only the minimum repository permissions required.
- Avoid sharing tokens, logs, screenshots, or configuration files that may contain sensitive information.
- Revoke old or unused tokens.
- Keep Git, Python, and the application dependencies updated.

## 16. Children's Privacy

Git Automation Pro is a developer productivity tool and is not directed at children.

The application does not knowingly collect personal information from children.

## 17. Changes to This Policy

This Privacy Policy may be updated from time to time.

When changes are made, the updated version should be committed to the project repository with a new "Last updated" date.

## 18. Contact

For questions about this Privacy Policy, please contact:

**Project maintainer:** [Your Name or Organization]  
**Email:** [Your Contact Email]  
**GitHub:** [Your GitHub Profile or Repository URL]

---

This Privacy Policy is provided as a general template for Git Automation Pro. It should be reviewed and adjusted before publication, especially if the application is distributed publicly or submitted to a software store.
