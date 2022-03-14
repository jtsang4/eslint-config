# @jtsang/eslint-config

> Forked from [@antfu/eslint-config](https://github.com/antfu/eslint-config)

Opinionated eslint configs.

- Single quotes, no semi
- Auto fix for formatting (aimed to be used standalone without Prettier)
- TypeScript, Vue, React out-of-box
- Lint also for json, yaml, markdown
- Sorted imports, dangling commas for cleaner commit diff
- Reasonable defaults, best practices, only one-line of config

[![npm](https://img.shields.io/npm/v/@jtsang/eslint-config?color=a1b858&label=)](https://npmjs.com/package/@jtsang/eslint-config)

## Usage

### Install

```bash
pnpm add -D eslint @jtsang/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": ["@jtsang"]
}
```

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint ."
  }
}
```

### Config VS Code auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```

## Check Also

- [antfu/vscode-settings](https://github.com/antfu/vscode-settings) - [Antfu](https://github.com/antfu)'s VS Code settings
- [antfu/ts-starter](https://github.com/antfu/ts-starter) - [Antfu](https://github.com/antfu)'s starter template for TypeScript library
- [antfu/vitesse](https://github.com/antfu/vitesse) - [Antfu](https://github.com/antfu)'s starter template for Vue & Vite app

## License

MIT
