# @m1rn/tsconfig

<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/137921275/258572450-d0a2270e-45ad-4ed4-aed0-b5c0a2eea988.svg" width="100" height="100" align="right" alt="TypeScript" />

[![Version](https://img.shields.io/npm/v/@m1rn/tsconfig?color=1976d2&label=)](https://www.npmjs.com/package/@m1rn/tsconfig)
[![License](https://img.shields.io/npm/l/@m1rn/tsconfig?color=1976d2&label=)](LICENSE.md)

A collection of TypeScript preset configurations that follow best practices, designed to help you quickly set up your TypeScript projects.

## Features

- **Best Practices**: Ensures accurate and reliable type checking.
- **Strict Configurations**: Keeps your code quality at a high standard.
- **Flexible Setup**: Adapts to various project needs.
- **Regular Updates**: Stays up-to-date with the latest features and versions.

## Prerequisites

### TypeScript

- Version >= 5.0.0

## Installation

```bash
npm install @m1rn/tsconfig --save-dev
```

## Presets

- [`@m1rn/tsconfig/base`](./base/tsconfig.json)

  Suitable for all TypeScript projects; serves as foundation for other presets

- [`@m1rn/tsconfig/strict`](./strict/tsconfig.json)

  Suitable for projects that require strict type checking.

- [`@m1rn/tsconfig/browser`](./browser/tsconfig.json)

  Suitable for browser environment projects.

- [`@m1rn/tsconfig/node`](./node/tsconfig.json)

  Suitable for Node.js projects.

- [`@m1rn/tsconfig/react`](./react/tsconfig.json)

  Suitable for React projects.

- [`@m1rn/tsconfig/vue`](./vue/tsconfig.json)

  Suitable for Vue projects.

## Usage

Just `extend` the preset configurations you need in your `tsconfig.json` file:

### Single Configuration

```json
{
  "extends": "@m1rn/tsconfig/base"
}
```

### Combined Configuration

```json
{
  "extends": ["@m1rn/tsconfig/node", "@m1rn/tsconfig/strict"]
}
```

## See Also

- [@m1rn/eslint-config](https://github.com/m1rn/eslint-config)

## License

[MIT](LICENSE.md) License &copy; 2024-PRESENT [m1rn](https://github.com/m1rn)
