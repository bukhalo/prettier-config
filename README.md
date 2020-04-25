# Personal prettier configuration by [Aleksandr Bukhalo](https://github.com/bukhalo)

## How to use
**Define this package as Prettier config in your `package.json`**:
```jsonc
{
  // ...
  "prettier": "@bukhalo/prettier-config"
}
```

**Or require this package in your `.prettierrc.js`, if you want to overwrite some properties of this configuration**:
```js
module.exports = {
  ...require("@bukhalo/prettier-config"),
  semi: false
};
```
