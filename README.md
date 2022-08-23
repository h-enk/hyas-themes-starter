# Hyas starter theme

Starter theme for Hyas sites.

## Status

[![npm (scoped)](https://img.shields.io/npm/v/@hyas/themes-starter?style=flat-square)](https://www.npmjs.com/package/@hyas/themes-starter) [![GitHub Workflow Status](https://img.shields.io/github/workflow/status/h-enk/hyas-themes-starter/CodeQL?style=flat-square)]((https://github.com/h-enk/hyas-themes-starter/actions/workflows/codeql.yml))

## Installation

```bash
npm i @hyas/themes-starter -D
```

## Setup

Add to `./config/_default/module.toml`:

```toml
[[mounts]]
  source = "layouts"
  target = "layouts"

[[mounts]]
  source = "node_modules/@hyas/themes-starter/layouts"
  target = "layouts"
```

Add to `./config/_default/config.toml`:

```toml
disableKinds = ['taxonomy', 'term']
```

## Usage

See the Hyas docs: [Themes](https://gethyas.com/docs/reference-guides/themes/)


## Credits

Based on [Really getting started with Hugo](https://www.brycewray.com/posts/2022/07/really-getting-started-hugo/) by Bryce Wray.
