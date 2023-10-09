# pilutech-base-pack README

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more info
* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**

- Para Configurar o vs code

```json
{
  // Tamanho das fontes dos terminal integrado
  "terminal.integrated.fontSize": 16,
  "workbench.startupEditor": "newUntitledFile",
  "polacode.backgroundColor": "#734949",
  "codesnap.backgroundColor": "#BF3636",
  "codesnap.shutterAction": "copy",
  "editor.tabSize": 2,
  "editor.fontSize": 18,
  "editor.lineHeight": 26,
  "editor.fontLigatures": true,
  "editor.semanticHighlighting.enabled": true,
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.tabSizing": "shrink",
  "workbench.editor.labelFormat": "short",
  "extensions.ignoreRecommendations": true,
  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": true,
  "explorer.confirmDragAndDrop": false,
  "editor.rulers": [],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.addMissingImports": true,
    "source.organizeImports": true
  },
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true
    // "**/node_modules": true
  }
  "[markdown]": {
    "editor.defaultFormatter": "vscode.markdown-language-features"
  },
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma",
    "editor.formatOnSave": true
  },
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json",
    "*.tsx": "typescriptreact",
    ".env.*": "dotenv",
    "*.css": "css"
  },
  //pathComplete
  "typescript.suggest.paths": false,
  "javascript.suggest.paths": false,
  "path-intellisense.extensionOnImport": true,
  "path-intellisense.showHiddenFiles": true,
  //Emmet
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "emmet.triggerExpansionOnTab": true,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  //Colorize Native
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "editor.guides.highlightActiveIndentation": "always",
  //Gitlens
  "gitlens.codeLens.recentChange.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "git.enableSmartCommit": true,
  "liveshare.featureSet": "insiders",
  "typescript.tsserver.log": "off",
  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
  "material-icon-theme.activeIconPack": "nest",
  "screencastMode.onlyKeyboardShortcuts": true,
  "material-icon-theme.folders.associations": {
    "infra": "app",
    "entities": "class",
    "domain": "class",
    "schemas": "class",
    "typeorm": "database",
    "repositories": "mappings",
    "http": "container",
    "migrations": "tools",
    "modules": "components",
    "implementations": "core",
    "dtos": "typescript",
    "fakes": "mock",
    "websockets": "pipe",
    "protos": "pipe",
    "grpc": "pipe",
    "providers": "include",
    "subscribers": "messages",
    "useCases": "controller",
    "kafka": "scripts",
    "mappers": "meta",
    "_shared": "shared",
    "eslint-config": "tools",
    "kube": "kubernetes"
  },
  "tabnine.experimentalAutoImports": true,
  "cSpell.enableFiletypes": [
    "!asciidoc",
    "!c",
    "!cpp",
    "!csharp",
    "!go",
    "!handlebars",
    "!haskell",
    "!jade",
    "!java",
    "!latex",
    "!php",
    "!pug",
    "!python",
    "!restructuredtext",
    "!rust",
    "!scala",
    "!scss"
  ],
  "cSpell.language": "pt-BR",
  "editor.suggestSelection": "first",
  "liveServer.settings.donotVerifyTags": true,
  "cSpell.userWords": [
    "chakra",
    "Checkboxy",
    "codesnap",
    "diego",
    "donot",
    "dtos",
    "esbenp",
    "fastify",
    "Gameplay",
    "instagram",
    "jakeliny",
    "Jakeliny",
    "Jamjuree",
    "kube",
    "kubernetes",
    "larazevedo",
    "liveshare",
    "Mayk",
    "maykbrito",
    "mentoria",
    "Mentoria",
    "middlewares",
    "Monokai",
    "originalname",
    "ormconfig",
    "Parens",
    "pilu",
    "piluvitu",
    "polacode",
    "Pomodoro",
    "prefetch",
    "ricci",
    "Ricci",
    "Roboto",
    "rocketnotes",
    "rocketseat",
    "screencast",
    "sequelizerc",
    "smoothing",
    "stylelintrc",
    "Stylesheet",
    "tabnine",
    "tailwindcss",
    "typeorm",
    "upsert",
    "websockets"
  ],
  "terminal.integrated.showExitAlert": false,
  "security.workspace.trust.untrustedFiles": "newWindow",
  "files.autoSave": "afterDelay",
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "git.confirmSync": false,
  "prettier.proseWrap": "never",
  "terminal.integrated.defaultProfile.windows": "Ubuntu (WSL)",
  "editor.wordWrap": "bounded",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.fullReload": true,
  "liveServer.settings.CustomBrowser": "chrome",
  "cSpell.caseSensitive": true,
  "cSpell.enabled": true,
  "editor.fontWeight": "normal",
  "editor.fontFamily": "JetBrains Mono",
  "editor.linkedEditing": true,
  "editor.stickyScroll.enabled": true,
  "zenMode.centerLayout": false,
  "zenMode.fullScreen": false,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "emmet.excludeLanguages": [],
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.useInlineCompletions": true,
  "editor.accessibilitySupport": "off",
  "material-icon-theme.folders.theme": "specific",
  "path-intellisense.autoTriggerNextSuggestion": true,
  "cSpell.showAutocompleteSuggestions": true,
  "tailwindCSS.emmetCompletions": true,
  "html-css-class-completion.enableEmmetSupport": true,
  "emmet.showExpandedAbbreviation": "always",
  "workbench.colorTheme": "63fe4617-4cac-47a5-9b93-6794514c35ad",
  "workbench.iconTheme": "symbols",
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  "editor.acceptSuggestionOnCommitCharacter": false,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql"
  ],
  "polacode.transparentBackground": true,
  "polacode.target": "snippet",
  "editor.minimap.enabled": false,
  "update.mode": "start",
  "terminal.integrated.gpuAcceleration": "off",
  "terminal.integrated.defaultProfile.osx": "fish",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "workbench.editor.untitled.hint": "hidden",
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "window.commandCenter": true,
  "git.openRepositoryInParentFolders": "always",
  // Discord Rich Presence
  "vscord.app.name": "Visual Studio Code",
  "vscord.status.details.text.idle": "Dando uma descansada, pq ngm é de ferro 🤓",
  "workbench.productIconTheme": "fluent-icons",
  "debug.disassemblyView.showSourceCode": false,
  "gitlens.hovers.currentLine.over": "line",
  "figma.autocompleteBlocks": true,
  "symbols.hidesExplorerArrows": false,
  "terminal.integrated.env.linux": {},
  "console-ninja.featureSet": "Pro",
  "console-ninja.toolsToEnableSupportAutomaticallyFor": {
    "live-server-extension": true,
    "live-preview-extension": true
  },
  "console-ninja.maxLogViewerEntries": 10,
  "workbench.editor.empty.hint": "hidden",
}
```