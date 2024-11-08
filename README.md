
> :warning: **Deprecation Notice** :warning:
> This repository has been deprecated. Please use the corresponding package from the [iLib-js monorepo](https://github.com/iLib-js/ilib-mono) instead.

# ilib-loctool-html

Ilib loctool plugin to parse and localize static HTML files

## License

This plugin is license under Apache2. See the [LICENSE](./LICENSE)
file for more details.

## Release Notes

### v1.0.6

- update dependencies
- fixed a bug where a dependency was imported incorrectly causing
  exceptions

### v1.0.5

- update dependencies
- convert unit tests from nodeunit to jest

### v1.0.4

- update dependencies
- use the loctool's logger instead of its own

### v1.0.3

- Fix a bug where the pseudo locales were not initialized properly.
  This fix gets the right set of locales from the project settings to
  see if any of them are pseudo locales.

