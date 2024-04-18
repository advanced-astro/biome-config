# biome-config-astro

Shared Biome config for Astro projects

## Usage

### Installation

```bash
npm|yarn|pnpm|bun add -D @biomejs/biome biome-config-astro
```

Add the `extends` array to your project's `biome.json` file:

```jsonc
// <project-root>/biome.json
{
    "$schema": "https://biomejs.dev/schemas/1.7.0/schema.json",
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

- [License (ISC)](LICENSE.md)
- [Astro][astro-site]
- [Biome][biome-site]

[astro-site]: https://astro.build
[biome-site]: https://biome.dev
