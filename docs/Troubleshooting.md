This section identifies and diagnoses technical issues that may prevent the application from functioning properly. Below are some common problems you might have encountered:

| Issues                              | Possible Causes                                                                                     | Solutions                                                                 |
|--------------------------------------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| Unable to clone a GitHub repository to a local directory | GitHyb repository URL is incorrect or not properly formatted. | Double-check the repository URL. Ensure it ends with `.git`. |
| "Repository Already Exists" or "Directory Not Empty" errors | The destination directory in your local computer contains conflicting files. | Clear the destination directory before cloning the repository. |
| Unable to push commits to GitHub         | Your GitHub account is not configured properly in VS Code.         | Ensure your GitHub credentials are correctly set up in VS Code. If not, click on [View] → [Command Palette], and then select [GitHub: Sign in to GitHub] to reconfigure your GitHub account in VS Code. |
| | You do not have the write access to the remote repository. | Check with the repository owner to confirm your access rights.
| Extensions not working               | There are corrupted installation, conflicting extensions, outdated version, or system issues.                | Disable and re-enable the extension, check for updates, and restart the application. |
| Keyboard shortcuts not working    | Multiple actions are assigned to the same key combination.          | Resolve the key conflicts as instructed in [Customized Keyboard Shortcuts](keyboard_shortcuts.md). |
| Unable to remove a keybinding | There are bugs or technical issues with the keybinding configuration. |  Go to [File] → [Preferences] → [Keyboard Shortcuts] → [Open Keyboard Shortcuts (JSON)] to manually remove the keybinding from the keybindings.json file.

