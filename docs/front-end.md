# Front End Notes

[[TOC]]

## Pre-Requistites

- nvm --version `0.33.11`
- node --version `v10.0.0`
- npm --version `5.6.0`


## Setup Steps

Install Homebrew

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install NVM (Node Version Manager)

```shell
brew install nvm
```

Install Node

```shell
nvm install 10
```

Use Node 10

```shell
nvm use 10
```

Some of the follow steps can be found here: [React &amp; Webpack](https://www.typescriptlang.org/docs/handbook/react-&-webpack.html)

Install WebPack

```shell
npm i -g webpack-cli
```

Install React Types for TypeScript

```shell
npm i --save react react-dom @types/react @types/react-dom
```

Install development helpers

```shell
npm i --save typescript awesome-typescript-loader source-map-loader
```