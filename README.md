# Commitlint Config 🚔🚨

A extensible shared configuration to enforcing commit pattern using [Commitlint](https://commitlint.js.org/).

![](https://github.com/pontte/commitlint-config/workflows/promote-prod-from-preprod-branch/badge.svg)

## Install

### npm

```sh
npm install @pontte/commitlint-config --save-dev
```

### yarn

```sh
yarn add @pontte/commitlint-config --dev
```

## Usage

Add package to your `.commitlint.js` or [commitlint](https://commitlint.js.org/#/guides-local-setup?id=install-commitlint) configuration file.

```js
module.exports = {
  extends: ['@pontte/commitlint-config'],
};
```
