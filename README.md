# @jtsang/eslint-config

> Forked from [@antfu/eslint-config](https://github.com/antfu/eslint-config)

[![npm](https://img.shields.io/npm/v/@jtsang/eslint-config)](https://npmjs.com/package/@jtsang/eslint-config)

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

### Config `.eslintignore`

```txt
dist
public
```

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint \"**/*.{vue,ts,js}\""
  }
}
```

### Config VSCode auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
