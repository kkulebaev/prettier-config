# @kkulebaev/prettier-config

A Prettier [shareable config](https://prettier.io/docs/en/configuration.html#sharing-configurations )
for projects using **[Prettier](https://prettier.io/ )**

## Installation

```
npm install --save-dev @kkulebaev/prettier-config
```

_This is only a shareable configuration. It does not install Prettier or any other part of the tool chain._

## Usage

Reference it in `package.json` using the `prettier` property:

```json
{
  "name": "my-projects-name",
  "prettier": "@kkulebaev/prettier-config",
  "devDependencies" : {
    "@kkulebaev/prettier-config": "^0.1.0"
  }
}
```

If you don't want to use `package.json`, you can use any of the supported
extensions to export a string:

```jsonc
// `.prettierrc.json`
"@kkulebaev/prettier-config"
```

```javascript
// `prettier.config.js` or `.prettierrc.js`
module.exports = '@kkulebaev/prettier-config'
```
