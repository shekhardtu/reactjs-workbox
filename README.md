# ReactJS Extension Pack for VSCode

The ReactJS Extension Pack for Visual Studio Code is a collection of extensions specifically designed for web developers who work with the ReactJS library. This extension pack includes a range of useful tools and features to help streamline the development process and improve productivity.

## Included Extensions

The ReactJS Extension Pack includes the following extensions:

1. **[Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)** - a collection of code snippets for ReactJS development that can be easily inserted into your code to speed up development.
2. **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)** - a linter that helps ensure that your code follows best practices and is free from errors.
3. **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** - a code formatter that helps ensure that your code is consistent and easy to read.
4. **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)** - an extension that automatically rename HTML/XML tags for you as you type, saving time and reducing errors.
5. **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)** - an extension that provides advanced Git capabilities within Visual Studio Code, allowing you to easily track changes and collaborate with others.
6. **[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)**
7. **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**
8. **[npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)**

9. **[christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)**

## Paste these recommended settings in VS code workspace settings to supercharged your vs code.

## Shortcut to access workspace settings ` ⌘+,`

```JSON

  {
  "eslint.enable": true,
  "files.trimTrailingWhitespace": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "html",
    "typescriptreact"
  ],
  "eslint.format.enable": true,
  "eslint.codeActionsOnSave.mode": "problems",

  "prettier.bracketSpacing": true,
  "prettier.printWidth": 80,
  "prettier.singleQuote": true,
  "prettier.semi": false,
  "prettier.trailingComma": "es5",
  "prettier.tabWidth": 2,
  "prettier.useTabs": false,
  "prettier.bracketSameLine": false,
  "editor.insertSpaces": true,
  "editor.formatOnSave": true, // only if you want auto      //fomattting on saving the file
  "editor.detectIndentation": true,
  "editor.tabSize": 2,
  "editor.formatOnPaste": false,
  "editor.formatOnType": true,
  "editor.renderControlCharacters": true,
  "editor.renderWhitespace": "all",
  "files.exclude": {
    "**/node_modules": true, // enable/disable as per your need
    ".gitignore": true, // enable/disable as per your need
    ".eslintignore": true, // enable/disable as per your need
    ".eslintrc.js": false, // enable/disable as per your need
    ".babelrc": true, // enable/disable as per your need
    ".editorconfig": true,
    ".postcssrc.js": true,
    ".jshintrc": true,
    "build": true,
    ".github": true,
    ".idea": true
  },
  "editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  }
}


```

With the ReactJS Extension Pack, you'll have everything you need to develop high-quality ReactJS applications quickly and efficiently, all within the convenience of the Visual Studio Code editor.
