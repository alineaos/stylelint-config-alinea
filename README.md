# styelint-config-alinea

Stylelint rules shared across Alinea OpenSource TypeScript projects

## Usage

### Installation

```shell
  yarn add --dev stylelint @alineaopensource/stylelint-config-alinea
```

### Configuration

- Add a `stylelint.config.js` file to the root of you project and paste the following code inside of it:

> Note that _ignoredFiles_ are just examples. You should define your own `ignoreFiles`.

```javascript
module.exports = {
  extends: "stylelint-config-alinea",
  ignoreFiles: [
    "./coverage/**/*",
    "./dist/**/*",
    "./node_modules/**/*",
    "./src/**/__snapshots__/**/*"
  ]
};
```
