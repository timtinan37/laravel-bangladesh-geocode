# Bangladesh Geocode
Division, District and Upazila data of Bangladesh for Laravel application.
Migration and Seeds are ready. Just publish migrations and seeds and then migrate the db and run the seed command.

[![Latest Version on Packagist](https://img.shields.io/packagist/v/devfaysal/laravel-bangladesh-geocode.svg?style=flat-square)](https://packagist.org/packages/devfaysal/laravel-bangladesh-geocode)
[![Build Status](https://img.shields.io/travis/devfaysal/laravel-bangladesh-geocode/master.svg?style=flat-square)](https://travis-ci.org/devfaysal/laravel-bangladesh-geocode)
[![Quality Score](https://img.shields.io/scrutinizer/g/devfaysal/laravel-bangladesh-geocode.svg?style=flat-square)](https://scrutinizer-ci.com/g/devfaysal/laravel-bangladesh-geocode)
[![Total Downloads](https://img.shields.io/packagist/dt/devfaysal/laravel-bangladesh-geocode.svg?style=flat-square)](https://packagist.org/packages/devfaysal/laravel-bangladesh-geocode)


## Installation

You can install the package via composer:

```bash
composer require devfaysal/laravel-bangladesh-geocode

```
Publish Migration and Seeds

```bash
php artisan vendor:publish --provider="Devfaysal\BangladeshGeocode\BangladeshGeocodeServiceProvider"

```

## Usage

``` php
use Devfaysal\BangladeshGeocode\Models\Division;
use Devfaysal\BangladeshGeocode\Models\District;
use Devfaysal\BangladeshGeocode\Models\Upazila;

$divisions = Division::all();
$districts = District::all();
$upazilas = Upazila::all();

Use any Laravel model functions...
```

### Testing

``` bash
composer test
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email devfaysal@gmail.com instead of using the issue tracker.

## Credits

- [Faysal Ahamed](https://github.com/devfaysal)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## Laravel Package Boilerplate

This package was generated using the [Laravel Package Boilerplate](https://laravelpackageboilerplate.com).
