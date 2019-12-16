# Lerna independent mode monorepo auto POC

POC repo for testing out automated npm packages release **directly when a PR is merged** with https://github.com/intuit/auto.

## Caveats

- Lerna monorepo with independent mode will do canary releases for **all packages** even the ones not changed, see https://github.com/intuit/auto/issues/748
