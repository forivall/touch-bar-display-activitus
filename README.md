# Touch Bar Display Commands - Activitus fork

Fork of touch-bar-display to use https://github.com/Gruntfuggly/activitusbar 's commands.

[![Latest Release](https://vsmarketplacebadge.apphb.com/version/blairleduc.touch-bar-display.svg)](https://marketplace.visualstudio.com/items?itemName=blairleduc.touch-bar-display)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/blairleduc.touch-bar-display.svg)](https://marketplace.visualstudio.com/items?itemName=blairleduc.touch-bar-display)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/blairleduc.touch-bar-display.svg)](https://marketplace.visualstudio.com/items?itemName=blairleduc.touch-bar-display#review-details)
![Licence](https://img.shields.io/github/license/BlairLeduc/touch-bar-display.svg)

Adds the following commands to the touchbar:

![Touch Bar Example](media/touch-bar-example.png)

These commands automatically hide during debugging to allow room for the debug commands.

# Installation
Open VS Code, run the this command:

    ext install touch-bar-display

# Do you have functionality that would help others?
Create a Pull Request, and I'll take a look.

# Also, apopros of nothing, here's my activitus views settings
```json
  "activitusbar.views": [
    {
      "name": "command.workbench.action.toggleActivityBarVisibility",
      "codicon": "suggest-more-info",
      "tooltip": "Show Activity Bar"
    },
    {
      "name": "explorer",
      "codicon": "files"
    },
    {
      "name": "debug",
      "codicon": "debug-alt"
    },
    {
      "name": "scm",
      "codicon": "source-control"
    },
    {
      "name": "remote",
      "codicon": "remote-explorer",
      "tooltip": "Remote Explorer"
    },
    {
      "name": "extensions",
      "codicon": "extensions"
    },
    {
      "name": "extension.atlascode-drawer",
      "codicon": "project",
      "tooltip": "Atlassian"
    },
    {
      "name": "extension.sqltoolsActivityBarContainer",
      "codicon": "database",
      "tooltip": "SQLTools"
    },
  ],
```
