# GIT SCOPE (Intellij Plugin)

Create custom "scopes" for any target branch. Selectable in a tool window, which is then called **GIT SCOPE**.
The Current "scope" is displayed as a
- diff in the tool window
- "line status" in the "line gutter"
- custom "scope" and finally as a
- status bar widget 

### Story
I think every developer loves to check their changes with **version control** before committing.
But there is a big problem after committing the code: All changes in **version control** and also the line status disappear completely.
Usually a branch contains more than one commit. This plugin helps you to make these commits visible again in an intuitive way!

### Modifications in Detail

![](docs/icon.svg) **Change Browser:**

Adds a tool window with a "change browser" (similar to version control) that displays the current diff of the **GIT SCOPE**.

![](docs/toolwindow.png)

![](docs/icon.svg) **Line Status Gutter:**

Adjusts the line status according to your **GIT SCOPE**. Normally this built-in feature shows only the current "HEAD" changes

READ: https://www.jetbrains.com/help/phpstorm/file-status-highlights.html

| HEAD               | "main"-Branch            |
|--------------------|--------------------------|
| ![](docs/head.png) | ![](docs/linestatus.png) |

![](docs/icon.svg) **Scope:**

Adds a custom *Scope* (used to do inspections, search/replace, ect), i.e. search results are filtered by **GIT SCOPE**.

READ: https://www.jetbrains.com/help/phpstorm/scopes.html

![](docs/scope.png)

![](docs/icon.svg) **Status Bar Widget**

To see the current selection of the Git Scope even when the tool window is not open, you can look at the status bar widget.

![](docs/statusbar.png)

## Shortcuts (Added by this Plugin)
|Shortcut| Description|
| --- |---|
| Alt+H | Toggle between HEAD and last git scope selection|

## More Useful Shortcuts
| Shortcut                                  | Description|
|-------------------------------------------|---|
| Ctrl+D (on any file in a changes browser) | Open diff window|
| F7                                        | step forward (in diff window)|
| Shift+F7                                  | step backward (in diff window)|
