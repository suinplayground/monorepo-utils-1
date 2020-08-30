# monorepo-utils [![Build Status](https://travis-ci.org/azu/monorepo-utils.svg?branch=master)](https://travis-ci.org/azu/monorepo-utils)

This repository is utilities for monorepo.
Also this repository is a monorepo.

## Packages

### [@monorepo-utils/package-utils](./packages/@monorepo-utils/package-utils)

Collect package file path in the monorepo.

Supports following package manager's workspaces.

- Lerna(`lerna.json`)
- Yarn's workspaces
- npm v7+'s workspaces

### [@monorepo-utils/collect-changelog](./packages/@monorepo-utils/collect-changelog)

[@monorepo-utils/collect-changelog](./packages/@monorepo-utils/collect-changelog) get change from each package's `CHANGELOG.md`.
It help to collect changelog in lerna's [Independent mode](https://github.com/lerna/lerna#independent-mode---independent).

## Deprecated Packages

### **Deprecated** <del>[@monorepo-utils/publish](./packages/@monorepo-utils/publish)</del>

[@monorepo-utils/publish](./packages/@monorepo-utils/publish) help npm publish.

This script split `lerna publish`(lerna 2) into versioning and publishing.

:warning: Notes:

lerna 3 support `lerna version` and `lerna publish`.
You should use lerna 3 directly.

