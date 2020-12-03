# A shared Prettier config

## Installation

```sh
npm install --save-dev @andgohq/prettier-config
```

## Usage

### Option 1

Add a key in your **package.json** file.

```json
{
  "prettier": "@andgohq/prettier-config"
}

```

### Option 2

Create a **prettier.config.js**.

```js
module.exports = {
  ...require("@andgohq/prettier-config");

  // ...
}
```
