English | [简体中文](./README.zh-Hans.md)

# @0x219/commitlint-config

⚙️ A shareable `commitlint` config enforcing [conventional commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/).

## Getting started

Install the package in your project directory with:

```bash
// with npm
npm install @commitlint/cli @0x219/commitlint-config --save-dev

// with yarn
yarn add @commitlint/cli @0x219/commitlint-config --save-dev
```

In commitlint.config.js:

```js
module.exports = {
  extends: ['@0x219'],
};
```

## Thanks

[commitlint](https://github.com/conventional-changelog/commitlint) - 📓 Lint commit messages.

## License

[MIT](./LICENSE) ⓒ Simon
