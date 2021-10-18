English | [简体中文](./README.zh-Hans.md)

# @0x219/commitlint-config

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) ![npm (scoped)](https://img.shields.io/npm/v/@0x219/commitlint-config?style=flat-square) ![npm](https://img.shields.io/npm/dm/@0x219/commitlint-config?color=yellow&style=flat-square) ![NPM](https://img.shields.io/npm/l/@0x219/commitlint-config?style=flat-square)

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

## Rules

The most common commit conventions follow this pattern:

```
<type>[optional scope]: <subject>

[optional body]

[optional footer(s)]
```

### Type
Type cannot be empty, must be lowercase.（`build` | `break` | `chore` | `ci` | `docs` | `feat` | `fix` | `perf` | `refactor` | `revert` | `release` | `style`  | `test` | `wip`）

### Subject
The subject cannot be empty and cannot end with. Never allowed "sentence-case", "start-case", "pascal-case", "upper-case".

### Body
There must be a space before the body, and the maximum length is 100.

### Footer
There must be a space before the footer, and the maximum length is 100.
## Thanks

[commitlint](https://github.com/conventional-changelog/commitlint) - 📓 Lint commit messages.

## License

[MIT](./LICENSE) ⓒ Taoist Priest
