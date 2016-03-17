# babel-preset-stage-0-kneden [![npm](https://img.shields.io/npm/v/babel-preset-stage-0-kneden.svg)](http://npm.im/babel-preset-stage-0-kneden)

> Babel `stage-0` preset, with async/await powered by [kneden](https://github.com/marten-de-vries/kneden) instead of regenerator.
>
> Automatically kept in sync with `babel-preset-stage-0` via [modify-babel-preset](https://github.com/developit/modify-babel-preset).


## Installation

```sh
$ npm i -S babel-preset-stage-0-kneden
```


## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["stage-0-kneden"]
}
```

### Via CLI

```sh
$ babel script.js --presets stage-0-kneden
```

### Via Node API

```javascript
require('babel-core').transform('code', {
  presets: ['stage-0-kneden']
});
```
