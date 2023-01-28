# GIT SCOPE (Intellij Plugin)
Provides a tool window and a status bar widget to select a target branch called **GIT SCOPE**
![](https://raw.githubusercontent.com/comod/git-scope/docs/docs/01_toolwindow.png)
# Story
I guess every developer loves to check their changes before commit using the **Version Control**.
But there is one big problem after committing code: All changes in the **Version Control** and also the Line Status completely disappear.
Usually one branch contains more than one commit. This plugin helps you to make these commits visible again in a intuitive way!

# Modifications

**Change Browser:**

Adds a tool window with a change browser (similar to Version Control) which shows the current diff of your **GIT SCOPE**

**Line Status:**

Adapts the Line Status according to your **GIT SCOPE**. Usually this built-in feature shows only the current "HEAD" changes

READ: https://www.jetbrains.com/help/phpstorm/file-status-highlights.html

**Scope:**

Adds a Custom *Scope* (inspections, search/replaces, ect) "Git Scope (Files)", which means search results will be filtered according to **GIT SCOPE**

READ: https://www.jetbrains.com/help/phpstorm/scopes.html

![](https://raw.githubusercontent.com/comod/git-scope/docs/docs/02_rollback.png)
![](https://raw.githubusercontent.com/comod/git-scope/docs/docs/03_scope.png)

## Useful Shortcuts
| Shortcut | Description |
| --- | --- |
| Alt+H | Toggle between HEAD and target branch |
| Ctrl+D (on any file in the changes browser) | Open diff window  
| F7 | step forward (in diff window)
| Shift+F7 | step backward (in diff window)
