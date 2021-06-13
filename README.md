<!-- [npm]: https://img.shields.io/npm/v/snowpack-plugin-template
[npm-url]: https://www.npmjs.com/package/snowpack-plugin-template
[size]: https://packagephobia.now.sh/badge?p=snowpack-plugin-template
[size-url]: https://packagephobia.now.sh/result?p=snowpack-plugin-template

[![npm][npm]][npm-url]
[![size][size]][size-url]
[![libera manifesto](https://img.shields.io/badge/libera-manifesto-lightgrey.svg)](https://liberamanifesto.com) -->

# snowpack-plugin-template

Snowpack plugin that processes JavaScript assets.

## Requirements

This plugin requires an [LTS](https://github.com/nodejs/Release) Node version (v8.0.0+) and Snowpack v2.0.0+.

## Install

Using npm:

```console
npm install --save-dev snowpack-plugin-template
```

## Usage

Create a `snowpack.config.js` [configuration file](https://www.snowpack.dev/reference/configuration) and import the plugin:

```js
const dsv = require('snowpack-plugin-template');

module.exports = {
  mount: {
    public: { url: '/', static: true },
    src: { url: '/dist' },
  },
  plugins: ['snowpack-plugin-template'],
};
```

## Options

### `bundle`

Type: `boolean`<br>
Default: `true`

Do you want a bundle or not?

## Meta

[LICENSE (MIT)](./LICENSE.md)
