# VSCode-setup

<img src="./installed ext.png"/>
<img src="./installed ext2.png"/>

### Extensions
- **[Bracket Pair Colorizer]( https://github.com/CoenraadS/Bracket-Pair-Colorizer-2)**
- **[Version Lens]( https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**
- **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)**
- **[ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)**
- **[indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)**
- **[MDX](https://marketplace.visualstudio.com/items?itemName=silvenon.mdx)**
- **[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)**
- **[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)**
- **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)**
- **[PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)**
- **[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)**
- **[Highlight matching tags ](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)**
[<img src="https://images2.imgbox.com/c6/c3/sLkQluHb_o.png"/>](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)
- **[Jupter notebook for vscode](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)**
- **[Vscode Icon😎](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icon)**

### settings for my vscode
```
{
  "git.autofetch": true,
  "json.schemas": [
    {
      "fileMatch": ["/myfile"],
      "url": "schemaURL"
    }
  ],
  "javascript.updateImportsOnFileMove.enabled": "always",
  "php.validate.executablePath": "C:/xampp/php/php",

  "auto-rename-tag.activationOnLanguage": [
    "javascriptreact",
    "html",
    "xml",
    "php",
    "javascript",
    "python"
  ],
  "files.autoSave": "off",
  "editor.tabSize": 1,
  "editor.wordWrap": "on",
  "terminal.integrated.fontSize": 14,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "editor.minimap.enabled": false,
  "prettier.jsxSingleQuote": true,
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.cursorBlinking": "expand",
  "launch": {
    "configurations": [],
    "compounds": []
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "security.workspace.trust.untrustedFiles": "open",
  "editor.bracketPairColorization.enabled": true,
  "editor.inlineSuggest.enabled": true,
  "jupyter.askForKernelRestart": false,
  "[python]": {
    "editor.defaultFormatter": "ms-python.python"
  },
  "tailwindCSS.includeLanguages": {
    "plaintext": "html,javascript,typescript"
  },
  "explorer.confirmDelete": false,
  "workbench.iconTheme": "vscode-icons",
  "editor.largeFileOptimizations": false,
  "gitlens.defaultDateLocale": null,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.codeActionsOnSave": {},
  "todo-tree.highlights.defaultHighlight": {
    "icon": "alert",
    "type": "text",
    // "foreground": "red",
    // "background": "white",
    "opacity": 50,
    "iconColour": "blue"
  },
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "icon": "check",
      "type": "line",
      "background": "green",
      "foreground": "white"
    },
    "FIXME": {
      "foreground": "black",
      "iconColour": "yellow",
      "background": "yellow",
      "gutterIcon": true
    }
  }
}


```
