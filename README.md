# prettier-config

WISEflow's base Prettier config.

## Installation

```sh
yarn add --dev prettier @uniwise/prettier-config
```

## Usage

After installing, update your project's `.prettierrc.js` file to import the rule sets you want:

```js
module.exports = {
  ...require('@uniwise/prettier-config'),
  // your overrides here
};
```

---

Read the [Prettier config docs](https://prettier.io) for more information.
