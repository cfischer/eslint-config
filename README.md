# eslint-config

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html)


## Installation

```
$ npm install --save-dev eslint eslint-config-cfischer
```


## Usage

Once the `eslint-config-cfischer` package is installed, you can use it by specifying `cfischer` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "cfischer",
  "rules": {
    // Additional, per-project rules...
  }
}
```


## License

Apache-2 © Christian Fischer
