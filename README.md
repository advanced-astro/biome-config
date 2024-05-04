# biome-config-astro

[![Install Size][pkgphobia-img]][pkgphobia-url]
[![NPM Package Version][npm-version]][npm-package]
[![License: ISC][license-img]][license]
[![GitHub Repo Stars][gh-stars]][gh-repo]

Shared Biome config for Astro projects

## Usage

### Installation

```sh
(bun|npm|pnpm|yarn) add -D @biomejs/biome biome-config-astro
```

Add the `extends` array to your project's `biome.json` file:

```jsonc
// <project-root>/biome.json
{
    "$schema": "https://biomejs.dev/schemas/1.7.2/schema.json",
    "extends": ["biome-config-astro"],
    // ...
}
```

Add scripts to your `package.json` if you haven't already:

```jsonc
// <project-root>/package.json
{
    //...
    "scripts": {
        "format": "biome format . --write",
        "lint": "biome lint .",
        "lint:fix": "biome lint . --apply",
        "lint:fix:unsafe": "biome lint . --apply-unsafe"
    }
    // ...
}
```

## Links

- [Astro][astro-site]
- [Biome][biome-site]
  - [Blog: Announcing Biome](https://biomejs.dev/blog/annoucing-biome/)

## License

[MIT](./LICENSE) License &copy; 2024 [Marc Redwerkz](https://github.com/rdwz)

[astro-site]: https://astro.build
[biome-site]: https://biome.dev
[gh-stars]: https://img.shields.io/github/stars/advanced-astro/biome-config
[gh-repo]: https://github.com/advanced-astro/biome-config
[license-img]: https://flat.badgen.net/github/license/amio/badgen
[license]: ./LICENSE.md
[npm-package]: https://www.npmjs.com/package/biome-config-astro
[npm-version]: https://img.shields.io/npm/v/biome-config-astro?style=flat-square
[pkgphobia-img]: https://packagephobia.com/badge?p=biome-config-astro&style=flat-square
[pkgphobia-url]: https://packagephobia.com/result?p=biome-config-astro
