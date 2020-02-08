## Webpack library bundle

Tutorial of how to author a library using [Webpack](https://webpack.js.org/guides/author-libraries/).

### Outline

This library exposes functionality to transalte numbers to words.
It is trivial code but the aim is to bundle it using webpack.

### Features

1. Bundling library code into all library targets ie CommonJS, AMD, ES2015 exports, UMD.
2. Having `lodash` as an external dependency.

### Dev notes

```
npm install --save-dev lodash webpack webpack-cli
```
