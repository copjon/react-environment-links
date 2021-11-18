# React Project and Workspace Helpers

## Package Management
### Yarn
Yarn is faster than npm as it manages dependencies in parallel rather than one at a time. Install globally using the following:
```
npm install -g yarn
```

## VSCode Plugins
### ESLint
[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
#### Setting up Auto Fix on Save
Auto Fix on Save - Auto Fix on Save is now part of VS Code's Code Action on Save infrastructure and computes all possible fixes in one round. It is customized via the editor.codeActionsOnSave setting. The setting supports the ESLint specific property source.fixAll.eslint. The extension also respects the generic property source.fixAll.
The setting below turns on Auto Fix for all providers including ESLint:

```
    "editor.codeActionsOnSave": {
        "source.fixAll": true
    }
```

In contrast, this configuration only turns it on for ESLint:
```
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    }
```

You can also selectively disable ESLint via:
```
    "editor.codeActionsOnSave": {
        "source.fixAll": true,
        "source.fixAll.eslint": false
    }
```

### Code Snippet Libraries
- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- [Jest Snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets)

## NPM Libraries
### AirBnB Style Guide
AirBnB maintains a widely used style guide along with tools to help maintain that style.
- Syle Guide - [airbnb/javascript](https://github.com/airbnb/javascript)
- NPM Package - [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)

