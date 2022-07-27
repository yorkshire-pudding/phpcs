# Backdrop Coding Standards

See the [official documentation](https://docs.backdropcms.org/php-standards)
 for Backdrop PHP coding standards.

## Installation

Work in progress, see https://github.com/backdrop/backdrop-issues/issues/5245

For now you can simply download the zip file or clone it locally. Put it
somewhere *outside* your Backdrop install.

## Usage

There are several ways to install the `phpcs` commandline tool in your dev
environment.
Somel Linux distributions provide a package (e.g. Debian php-codesniffer).
Make sure, the version is at least 3.5.

But you can also download phpcs from Github and put it in your $PATH.

Example usage for the current directory:

```
phpcs --standard=/path/to/phpcs_backdrop/Backdrop .
```
See full phpcs documentation in their Wiki:
https://github.com/squizlabs/PHP_CodeSniffer/wiki

Or run `phpcs --help` for a short overview.

## Issues

@todo

## Maintainers

@todo

## Credits

Created for Backdrop by Indigoxela.

[PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) is a project by
 Squiz Labs, licensed under BSD-3-Clause.

Several sniffs for the Backdrop ruleset have been forked from
[Drupal Coder](https://github.com/pfrenssen/coder), which is licensed under
 GPL-2.0-or-later.

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
