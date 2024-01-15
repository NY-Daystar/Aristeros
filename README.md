![GitHub watchers](https://img.shields.io/github/watchers/ny-daystar/aristeros)
![GitHub forks](https://img.shields.io/github/forks/ny-daystar/aristeros)
![GitHub Repo stars](https://img.shields.io/github/stars/ny-daystar/aristeros)
![GitHub repo size](https://img.shields.io/github/repo-size/ny-daystar/aristeros)
![GitHub language count](https://img.shields.io/github/languages/count/ny-daystar/aristeros)
![GitHub top language](https://img.shields.io/github/languages/top/ny-daystar/aristeros) <a href="https://codeclimate.com/github/ny-daystar/aristeros/maintainability"><img src="https://api.codeclimate.com/v1/badges/715c6f3ffb08de5ca621/maintainability" /></a>  
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/ny-daystar/aristeros/main)
![GitHub issues](https://img.shields.io/github/issues/ny-daystar/aristeros)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/ny-daystar/aristeros)
![GitHub](https://img.shields.io/github/license/ny-daystar/aristeros)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-blue.svg?style=circular)](#contributors)

![Javascript](https://img.shields.io/badge/logo-javascript-blue?logo=javascript&color=a5a5a5&logoColor=e5e5e5)

# Aristeros

TODO a revoir
Application developed in typescript (API) And Frontend (React)

Source code analysed with [DeepSource](https://deepsource.com/)

## Summary

-   [Requirements](#requirements)
-   [Get Started](#get-started)
-   [Debug](#debug)
    -   [Use Cypress UI](#use-cypress-ui)
    -   [Debug only one specification](#debug-only-one-specification)
-   [Configuration for get-links script](#configuration-for-get-links)
-   [For developpers](#for-developpers)
-   [Formatting](#formatting)
    -   [Setup Eslint](#setup-eslint)
    -   [Setup Prettier](#setup-prettier)
-   [Credits](#credits)

##### Version: 1.0.0

### Requirements

-   [NodeJS](http://nodejs.org) >= 20.3.1

## Get Started

1. Clone the repository

```bash
git clone https://github.com/NY-Daystar/aristeros.git
```

2. Install dependencies

```bash
npm install
```

## For developpers

TODO

## Formatting

The source code is format with the `prettier`
The source code is validate with `eslint`

### Setup EsLint

1. Install module

```bash
npm install --save-dev eslint
npm i -D @stylistic/eslint-plugin-js
```

2. Init eslint and configure it

```bash
npm init @eslint/config
# Setup: `To check syntax and find problems`
```

> BE CAREFUL setup only `To check syntax and find problems`

3. Rules are configured in, you can add it or modified following [this guide](https://eslint.org/docs/latest/rules/)

4. To see linter errors

```bash
npm run lint
```

5. To fix them

```bash
npm run lint:fix
```

### Setup Prettier

1. Install prettier

```bash
npm install --save-dev prettier
```

2. Init configuration file `.prettierrc`

```bash
file="./.prettierrc" && [ ! -f ${file} ] && node --eval "fs.writeFileSync('${file}','{}\n')"
```

Then add rules in `package.json` file like this

```js
"prettier": {
    "semi": false,
    "singleQuote": false,
    "trailingComma": "none",
    "tabWidth": 2
  },
```

## Credits

Made by Lucas NOGA.  
Licensed under GPLv3.
