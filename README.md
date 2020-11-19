# GARAIO Vue.js Extension Pack

This extension pack adds features for Vue.js development using Typescript.

## ESlint setup

### Install following packages

```bash
npm install --save-dev eslint vue-eslint-parser @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-vue eslint-plugin-prettier eslint-config-prettier
```

### Create/update eslint config

```ts
module.exports = {
  parser: "vue-eslint-parser",
  parserOptions: {
    parser: "@typescript-eslint/parser",
  },
  plugins: ["vue", "@typescript-eslint"],
  extends: [
    "eslint:recommended",
    "plugin:@typescript-eslint/eslint-recommended",
    "plugin:@typescript-eslint/recommended",
    "plugin:vue/recommended",
    "@vue/typescript/recommended",
    "@vue/prettier",
    "@vue/prettier/@typescript-eslint",
  ],
};
```

## Extensions Included in this pack

- [vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) -
  Vue tooling for VSCode
- [formulahendry.auto-complete-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag) -
  Extension Packs to add close tag and rename paired tag automatically for HTML/XML
- [JavaScript (ES6) Snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) -
  Code snippets for JavaScript in ES6 syntax
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) -
  Integrates ESLint into VS Code.
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) -
  VS Code plugin for prettier/prettier
- [Formatting toggle](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) - A VS Code extension that allows you to toggle the formatter on and off with a simple click
- [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets) - Snippets that will supercharge your Vue workflow
- ... some more

## Credits

All credits go to original authors of the above mentioned extensions and to the `mubaidr.vuejs-extension-pack` which served as an example.

**Happy Coding!**
