# Henrique's Personal ESLint Config

## Setup

1. Install the dependencies
```
npm i -D eslint eslint-config-henrique
```
or for **yarn**
```
yarn add -D eslint eslint-config-henrique
```
or for **pnpm**
```
pnpm install -D eslint eslint-config-henrique
```

2. Create a `.eslintrc.json` file extending the config for **React**:
<small>⚠️ Only use this is you're using **React**</small>

```
{
  "extends": "eslint-config-henrique/react"
}
```

3. Create a `.eslintrc.json` file extending the config for **NodeJS**:
<small>⚠️ Only use this is you're using **NodeJS**</small>
```
{
  "extends": "eslint-config-henrique/node"
}
```

> You can also use a `.eslintrc.js` instead of **JSON** if you prefer.

> This project is forked from [Rocketseat ESLint config](https://github.com/Rocketseat/eslint-config-rocketseat)