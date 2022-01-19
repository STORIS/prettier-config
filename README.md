# @storis/eslint-config

This package contains the standard prettier configurations for JavaScript and TypeScript packages used by [STORIS](https://www.storis.com).

## Installation

`@storis/prettier-config` is available as an [npm package](https://www.npmjs.org/package/@storis/prettier-config).

```sh
npm install @storis/prettier-config
```

## Usage

### Peer dependencies

The package relies on `prettier` as a peer dependency. You must ensure that a compatible version of the necessary peer dependency has been installed.

### Configuration

Add the following to `package.json`:

```
{
  "prettier": "@storis/prettier-config",
}
```

or modify the `.prettierrc.js` file:

```
const storisConfig = require('@storis/prettier-config);

module.exports = {
  ...storisConfig,
  ...
}
```

## License

This project is licensed under the terms of the [MIT license](/LICENSE).
