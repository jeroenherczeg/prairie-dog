# An Activity Stream Generator for Laravel 5

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Via Composer

``` bash
$ composer require jeroenherczeg/prairie-dog
```

## Usage

``` php
PrairieDog::forUser(1)->setPeriod('now','-1 hour')->generate();
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email jeroen@herczeg.be instead of using the issue tracker.

## Credits

- [Jeroen Herczeg][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/jeroenherczeg/prairie-dog.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/jeroenherczeg/prairie-dog/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/jeroenherczeg/prairie-dog.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/jeroenherczeg/prairie-dog.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/jeroenherczeg/prairie-dog.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/jeroenherczeg/prairie-dog
[link-travis]: https://travis-ci.org/jeroenherczeg/prairie-dog
[link-scrutinizer]: https://scrutinizer-ci.com/g/jeroenherczeg/prairie-dog/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/jeroenherczeg/prairie-dog
[link-downloads]: https://packagist.org/packages/jeroenherczeg/prairie-dog
[link-author]: https://github.com/jeroenherczeg
[link-contributors]: ../../contributors
