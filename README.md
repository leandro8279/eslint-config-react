## eslint-config-react

Shared ESLint configs for Web and Mobile projects.

## Installation

```sh
yarn add --dev @somosprte/eslint-config-react
```

You will also need to install `eslint` and `prettier`:

```sh
yarn add --dev eslint prettier
```

## Usage

Import this config into your own ESLint configuration using the `extends` option. ESLint checks both `package.json` and `.eslintrc.*` files for its configuration:

### package.json
```js
{
  "eslintConfig": {
    "extends": "@somosprte/eslint-config-react"
  }
}
```

### .eslintrc.js
```js
module.exports = {
  extends: '@somosprte/eslint-config-react',
};
```

## Customizing Prettier

If you would like to customize the Prettier settings, create a file named `.prettierrc` in your project directory. An example of Prettier configuration file:

```json
{
  "printWidth": 100,
  "tabWidth": 2,
  "singleQuote": true,
  "bracketSameLine": true
}
```

Read more about [configuring `prettier`](https://prettier.io/docs/en/configuration.html) and [all of the available options](https://prettier.io/docs/en/options.html).

