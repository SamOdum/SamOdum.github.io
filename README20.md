# Webpack Frontend Starterkit

A lightweight foundation for your next webpack based frontend project.

## Installation

```bash
npm install
```

## Start Dev Server

```bash
npm start
```

## Build Prod Version

```bash
npm run build
```

## Features

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
