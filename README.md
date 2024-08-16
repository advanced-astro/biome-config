# biome-config-astro

[![Install Size][pkgphobia-badge]][pkgphobia-url]
[![NPM Package Version][npm-badge]][npm-url]
[![License: ISC][license-badge]][license-file]
[![GitHub Repo Stars][gh-stars]][gh-repo]

[pkgphobia-badge]: https://packagephobia.com/badge?p=biome-config-astro
[pkgphobia-url]: https://packagephobia.com/result?p=biome-config-astro
[npm-badge]: https://img.shields.io/npm/v/biome-config-astro?style=flat-square
[npm-url]: https://www.npmjs.com/package/biome-config-astro
[license-badge]: https://flat.badgen.net/github/license/amio/badgen
[license-file]: ./LICENSE.md
[gh-stars]: https://img.shields.io/github/stars/advanced-astro/biome-config?style=flat-square
[gh-repo]: https://github.com/advanced-astro/biome-config

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
    // ...
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

- [Astro][astro-url]
- [Biome][biome-url]
  - [Blog: Announcing Biome](https://biomejs.dev/blog/annoucing-biome/)

## License

[ISC][license-file] License &copy; 2024 [Marc Redwerkz](https://github.com/rdwz)

[astro-url]: https://astro.build
[biome-url]: https://biome.dev
