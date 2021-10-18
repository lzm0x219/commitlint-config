[English](./README.md) | 简体中文

# @0x219/commitlint-config

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) ![npm (scoped)](https://img.shields.io/npm/v/@0x219/commitlint-config?style=flat-square) ![npm](https://img.shields.io/npm/dm/@0x219/commitlint-config?color=yellow&style=flat-square) ![NPM](https://img.shields.io/npm/l/@0x219/commitlint-config?style=flat-square)

⚙️ 一个强制执行[约定式提交](https://www.conventionalcommits.org/zh-hans/v1.0.0-beta.4/)的可共享 `commitlint` 配置。

## 快速开始

使用以下命令在项目目录中安装包：

```bash
// with npm
npm install @commitlint/cli @0x219/commitlint-config --save-dev

// with yarn
yarn add @commitlint/cli @0x219/commitlint-config --save-dev
```

在 commitlint.config.js 中:

```js
module.exports = {
  extends: ['@0x219'],
};
```

## 规则

最常见的提交约定遵循以下模式：
```
<类型>[可选 范围]: <描述>

[可选 正文]

[可选 脚注]
```

### 类型
类型不能为空，必须是小写。（`build` | `break` | `chore` | `ci` | `docs` | `feat` | `fix` | `perf` | `refactor` | `revert` | `release` | `style`  | `test` | `wip`）

### 描述
描述不能为空，也不能以.结束， 不允许“句子大小写”、“开始大小写”、“大写驼峰”、“大写字母”。

### 正文
可选，正文前必须有一个空格，最大长度为100。
### 脚注
可选，正文前必须有一个空格，最大长度为100。
## 致谢

[commitlint](https://github.com/conventional-changelog/commitlint) - 📓 Git提交消息分析工具

## 许可证

[MIT](./LICENSE) ⓒ Simon
