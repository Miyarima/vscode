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
- Tailwind CSS IntelliSense

## settings.json

```
{
  "files.eol": "\n",

  // Theme
  "workbench.iconTheme": "material-icon-theme",

  // Font
  "editor.fontFamily": "JetBrainsMono NFM",
  "scm.inputFontFamily": "JetBrainsMono NFM",
  "terminal.integrated.fontFamily": "JetBrainsMono NFM",
  "chat.editor.fontFamily": "JetBrainsMono NFM",
  "debug.console.fontFamily": "JetBrainsMono NFM",
  "notebook.output.fontFamily": "JetBrainsMono NFM",
  "markdown.preview.fontFamily": "JetBrainsMono NFM",
  "editor.inlayHints.fontFamily": "JetBrainsMono NFM",

  // APC
  "apc.activityBar": {
    "position": "bottom",
    "hideSettings": true,
    "size": 28
  },
  "apc.font.family": "JetBrainsMono NFM",
  "apc.statusBar": {
    "position": "editor-bottom",
    "height": 28,
    "fontSize": 12
  },
  "editor.linkedEditing": true,
  "breadcrumbs.filePath": "off",
  "editor.fontLigatures": true,
  "workbench.startupEditor": "none",
  "workbench.editor.wrapTabs": false,
  "editor.guides.bracketPairs": true,
  "workbench.editor.enablePreview": true,
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
  "editor.formatOnSave": true,
  "editor.stickyScroll.enabled": false,
  "breadcrumbs.enabled": false,
  "security.allowedUNCHosts": ["wsl.localhost"],
  "git.ignoreMissingGitWarning": true,
  "workbench.colorTheme": "Dracula Theme"
}

```
