# vscode-settings

## Preparing vscode  

#### Launching from the command line

You can also run VS Code from the terminal by typing 
'code' after adding it to the path:

  

- Launch VS Code.
- Open the Command Palette ```(fn + F1)``` and type 'shell command' to find
  the ```Shell Command: Install 'code'``` command in PATH command.

#### To list installed extensions
Open the terminal and write the next code:

To **see** the extensions:
```$ code --list-extensions```

To **install** the list of extensions:
``` $ code --install-extension (here paste de 'Current extensions list')```

  
## Extensions and Settings

### Current extensions
```
CoenraadS.bracket-pair-colorizer
dbaeumer.vscode-eslint
dsznajder.es7-react-js-snippets
eamodio.gitlens
esbenp.prettier-vscode
ms-vscode.vscode-typescript-tslint-plugin
PKief.material-icon-theme
Shan.code-settings-sync
SirTori.indenticator
```

### Font Family [Fira Code](https://github.com/tonsky/FiraCode)


### User Settings
```
{
"window.zoomLevel": 0,
"workbench.colorTheme": "Material Theme Darker",
"workbench.iconTheme": "material-icon-theme",
"editor.renderWhitespace": "all",
"gitlens.advanced.messages": {
	"suppressCommitHasNoPreviousCommitWarning": false,
	"suppressCommitNotFoundWarning": false,
	"suppressFileNotUnderSourceControlWarning": false,
	"suppressGitVersionWarning": false,
	"suppressLineUncommittedWarning": false,
	"suppressNoRepositoryWarning": false,
	"suppressResultsExplorerNotice": false,
	"suppressShowKeyBindingsNotice": true,
	"suppressUpdateNotice": false,
	"suppressWelcomeNotice": true
},
"explorer.confirmDelete": false,
"git.enableSmartCommit": true,
"problems.decorations.enabled": false,
"git.confirmSync": false,
"gitlens.keymap": "alternate",
"gitlens.codeLens.scopes": [
	"document",
	"containers"
],
"gitlens.hovers.currentLine.over": "line",
"editor.cursorWidth": 4,
"editor.cursorBlinking": "solid",
"editor.fontFamily": "'Fira Code', 'monospace'"
"terminal.integrated.fontFamily": "monospace",
"editor.wordWrap": "on",
"editor.fontSize": 16,
"editor.fontLigatures": true,
"editor.tabSize": 2,
"sync.gist": "7c0340291f9680dd33ac2609add3f8ed"
}
```