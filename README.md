# egg-compress-br
Support index.html for egg-static.

* **compress** base on `@koa/compress`.

## Installation

```
npm install egg-compress
```

```js
// config/plugin.js
exports.compress = {
  enable: true,
  package: 'egg-compress-br',
};
```

## Configuration

```js
// config/config.default.js
exports.compress = {};
```