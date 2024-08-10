# Rollup plugin Handlebars

This plugin uses Handlebars to compile templates.

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]

## ✨ Installation

1. **Add dependency to your project**

```shell
# Using pnpm
pnpm add rollup-plugin-handlebarsjs -D

# Using yarn
yarn add rollup-plugin-handlebarsjs -D

# Using npm
npm install rollup-plugin-handlebarsjs -D
```

2. **Create `shims.d.ts` file**

```typescript
declare module '*.hbs' {
  export default function (options: Record<string, any>): string
}
```

## ⚡ Usage

```typescript
import awsomeTemplate from './awsome-template.hbs'

const html = awsomeTemplate({ title: 'Hello, world!' })
```

## 🏆 Contributors

Here are some ways you can contribute:

- [Open an issue](https://github.com/hywax/rollup-plugin-handlebarsjs/issues/new/choose) to report a bug.
- [Create a pull request](https://github.com/hywax/rollup-plugin-handlebarsjs/compare) to add a new feature or fix a bug.

<a href="https://github.com/hywax/rollup-plugin-handlebarsjs/graphs/contributors">
  <img src="https://raw.githubusercontent.com/hywax/rollup-plugin-handlebarsjs/main/.github/static/contributors.svg" alt="Rollup plugin Handlebars Contributors" width="100%" />
</a>

## 📄 License

The Rollup plugin Handlebars is based on open source code, according to [MIT License](LICENSE).

[npm-version-src]: https://img.shields.io/npm/v/rollup-plugin-handlebarsjs/latest.svg?logo=hackthebox&color=4A4DFF&logoColor=fff
[npm-version-href]: https://npmjs.com/package/rollup-plugin-handlebarsjs
[npm-downloads-src]: https://img.shields.io/npm/dm/rollup-plugin-handlebarsjs.svg?colorB=4A4DFF
[npm-downloads-href]: https://npmjs.com/package/rollup-plugin-handlebarsjs
[license-src]: https://img.shields.io/badge/License-MIT-4A4DFF?logo=opensourceinitiative&logoColor=fff
[license-href]: https://npmjs.com/package/rollup-plugin-handlebarsjs
