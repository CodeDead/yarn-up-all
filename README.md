# yarn-up-all

![GitHub package.json version](https://img.shields.io/github/package-json/v/e5mode/yarn-up-all)
![GitHub](https://img.shields.io/github/license/e5mode/yarn-up-all)
![GitHub Releases](https://img.shields.io/github/downloads/e5mode/yarn-up-all/1.0.3/total)

## Description

This is a Yarn2 (Berry) plugin that will update all dependencies of a project with one simple command.

## Scripts

### `yarn build`

Creates a minified version of the `yarn-up-all` plugin and places it in the `./build` folder.

## Installation

Make sure that you have Yarn2 installed before using this plugin. You can install Yarn2 by running the following command in your terminal:

```Bash
yarn set version berry
```

In order to install the plugin, you can run the following command in your terminal:

```Bash
yarn plugin import https://github.com/e5mode/yarn-up-all/releases/download/1.0.3/index.js
```

### Usage

To update all dependencies (including `devDependencies`), run:

```Bash
yarn up-all
```

To exclude a single dependency, run:
```Bash
yarn up-all --exclude package
```

To exclude multiple dependencies:
```Bash
yarn up-all --exclude "package1 package2"
```
