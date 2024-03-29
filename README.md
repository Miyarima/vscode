# Settings for VSCode

## Extensions
- Apc Customize UI++
- Auto CLose Tag
- Bearded Theme
- Better Comments
- Material Icon Theme
- Prettier
- Rainbow CSV
- vscode-pigments

## settings.json

```
{
   "files.eol": "\n",

  // Theme
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Bearded Theme Vivid Black",

  // Font
  "editor.fontFamily": "jetBrains Mono",
  "scm.inputFontFamily": "jetBrains Mono",
  "terminal.integrated.fontFamily": "jetBrains Mono",
  "chat.editor.fontFamily": "jetBrains Mono",
  "debug.console.fontFamily": "jetBrains Mono",
  "notebook.output.fontFamily": "jetBrains Mono",
  "markdown.preview.fontFamily": "jetBrains Mono",
  "editor.inlayHints.fontFamily": "jetBrains Mono",

  // APC
  "apc.activityBar": {
    "position": "bottom",
    "hideSettings": true,
    "size": 28
  },
  "apc.font.family": "jetBrains Mono",
  "apc.statusBar": {
    "position": "editor-bottom",
    "height": 28,
    "fontSize": 12
  },
  "editor.linkedEditing": true,
  "breadcrumbs.filePath": "off",
  "editor.fontLigatures": true,
  "workbench.startupEditor": "none",
  "workbench.editor.wrapTabs": true,
  "editor.guides.bracketPairs": true,
  "workbench.editor.enablePreview": false,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairsHorizontal": false,

  // Random
  "editor.formatOnPaste": true,
  "svelte.enable-ts-plugin": true,
  "editor.minimap.enabled": false,
  "terminal.integrated.env.linux": {},
  "remote.autoForwardPortsSource": "hybrid",
  "editor.language.colorizedBracketPairs": [],
  "git.openRepositoryInParentFolders": "never",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "security.workspace.trust.untrustedFiles": "open",
  "[csharp]": {
    "editor.defaultFormatter": "csharpier.csharpier-vscode"
  },
  "editor.formatOnSave": true,
  "editor.stickyScroll.enabled": false,
  "breadcrumbs.enabled": false
}
```
