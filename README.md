# Prettier configuration by robotmafia team

## How to use
**Define this package as Prettier config in your `package.json`**:
```jsonc
{
  // ...
  "prettier": "@robotmafia-inc/prettier-config"
}
```

**Or require this package in your `.prettierrc.js`, if you want to overwrite some properties of this configuration**:
```js
module.exports = {
  ...require("@robotmafia-inc/prettier-config"),
  semi: false
};
```
