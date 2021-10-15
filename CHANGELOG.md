# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## v1.0.1 (2021-10-15)

#### ✅ Test
- Fix and pass type test cases.
#### 📝 Documentation
- Add package rule description.
- Add some badges for the package.
- Add package use cases.

## v1.0.0 (2021-10-15)

#### ✨ Features

- `rules`
  - Type: Type cannot be empty, must be lowercase.（`build` | `break` | `chore` | `ci` | `docs` | `feat` | `fix` | `perf` | `refactor` | `revert` | `release` | `style`  | `test` | `wip`）

  - Body: There must be a space before the body, and the maximum length is 100.

  - Footer: There must be a space before the footer, and the maximum length is 100.

  - Subject: The subject cannot be empty and cannot end with. Never allowed "sentence-case", "start-case", "pascal-case", "upper-case".
- `prompt`
  - Add type question.
  - Add scope question.
  - Add subject question.
  - Add body question.
  - Add break question.
  - Add issues question.
