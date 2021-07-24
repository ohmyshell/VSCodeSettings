# VSCodeSettings
My VSCode Settings

```jsonc
{
  // Telemetry off and disable some microsoft services.
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "workbench.enableExperiments": false,
  "workbench.settings.enableNaturalLanguageSearch": false,
  "code-runner.enableAppInsights": false,
  // font setup
  "editor.fontLigatures": true,
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 14,
  "editor.lineHeight": 30,
  // files config
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 60000,
  "files.exclude": {
    "**/node_modules": true,
    "**/build": true,
    "**/package-lock.json": true
  },
  // editor config
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.wordBasedSuggestions": false,
  "javascript.suggest.names": false,
  "editor.suggestSelection": "first",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.tabSize": 2,
  "workbench.colorTheme": "Min Dark",
  "prettier.singleQuote": true,
  "git.autofetch": true,
  "git.enableCommitSigning": true,
  // settings sync
  "sync.gist": "OOPS",
  // code runner config
  "code-runner.runInTerminal": true,
  "code-runner.saveAllFilesBeforeRun": true,
  "code-runner.ignoreSelection": true,
  // terminal config
  "terminal.integrated.rightClickBehavior": "selectWord",
  "terminal.integrated.shell.windows": "C:\\windows\\System32\\cmd.exe",
  // something config XD
  "window.zoomLevel": 0,
  // make zenmode cleaner (useful for screenshots) WIN + Shift + S.
  "zenMode.hideActivityBar": false,
  "zenMode.hideLineNumbers": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "docker.volumes.sortBy": "CreatedTime",
  "remote.extensionKind": {
    "ms-azuretools.vscode-docker": "workspace"
  },
  "editor.minimap.maxColumn": 30,
  "editor.minimap.size": "fill"
}

```
Theme min dark
