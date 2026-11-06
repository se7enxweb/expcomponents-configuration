# expcomponents-configuration

A component that allows you to use configuration files in different formats. The formats include the standard .ini file, and an array based format.

This is the Exponential fork of [zetacomponents/Configuration](https://github.com/zetacomponents/Configuration),
maintained by 7x (se7en.x) and the Exponential Foundation for Exponential and anyone else
who uses the Zeta Components Configuration component on current PHP versions. All credit for the
component goes to the Zeta Components authors listed in `composer.json` and `CREDITS`;
the upstream copyright notices (`NOTICE`) and the Apache License 2.0 (`LICENSE.txt`)
are kept unchanged.

## What is different from upstream

- The package is `se7enxweb/expcomponents-configuration` and replaces `zetacomponents/configuration`,
  so a project that requires the upstream package gets this one in its place.
- It requires the Exponential forks of the components it builds on (`se7enxweb/expcomponents-base`),
  which replace their upstream packages in the same way.
- The class names (`ezc*`) and the API are unchanged.
- Changes made in this fork are listed in `ChangeLog`.

## Installation

```bash
composer require se7enxweb/expcomponents-configuration
```

## Tests

```bash
composer update
vendor/bin/phpunit
```

The suite runs on every push for PHP 7.4, 8.0, 8.1, 8.2, 8.3, 8.4 and 8.5.

## License

Apache License 2.0, see `LICENSE.txt` and `NOTICE`.
