# [laravel-sitemap](https://github.com/pomirleanu/laravel-sitemap) package

[![Latest Stable Version](https://poser.pugx.org/pomirleanu/sitemap/version.png)](https://packagist.org/packages/pomirleanu/sitemap) [![Total Downloads](https://poser.pugx.org/pomirleanu/sitemap/d/total.png)](https://packagist.org/packages/pomirleanu/sitemap)  [![License](https://poser.pugx.org/pomirleanu/sitemap/license.png)](https://packagist.org/packages/pomirleanu/sitemap)

A not so simple sitemap generator for Laravel 5.


## Notes

Branch dev-master is for development and is UNSTABLE!

## Installation

Run the following command and provide the latest stable version (e.g v2.6.4) :

```bash
composer require pomirleanu/sitemap
```

or add the following to your `composer.json` file :

```json
"pomirleanu/sitemap": "2.6.*"
```

Then register this service provider with Laravel :

```php
'Pomirleanu\Sitemap\SitemapServiceProvider',
```

### Laravel 5.3 :

Service provider should be :

```php
Pomirleanu\Sitemap\SitemapServiceProvider::class,
```

Publish needed assets (styles, views, config files) :

```bash
php artisan vendor:publish --provider="Pomirleanu\Sitemap\SitemapServiceProvider"
```
*Note:* Composer won't update them after `composer update`, you'll need to do it manually!
