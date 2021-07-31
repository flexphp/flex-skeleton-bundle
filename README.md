# Skeleton-Bundle

[![Latest Stable Version](https://poser.pugx.org/flexphp/skeleton-bundle/v/stable)](https://packagist.org/packages/flexphp/skeleton-bundle)
[![Total Downloads](https://poser.pugx.org/flexphp/skeleton-bundle/downloads)](https://packagist.org/packages/flexphp/skeleton-bundle)
[![Latest Unstable Version](https://poser.pugx.org/flexphp/skeleton-bundle/v/unstable)](https://packagist.org/packages/flexphp/skeleton-bundle)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/flexphp/flex-skeleton-bundle/badges/quality-score.png)](https://scrutinizer-ci.com/g/flexphp/flex-skeleton-bundle)
[![Code Coverage](https://scrutinizer-ci.com/g/flexphp/flex-skeleton-bundle/badges/coverage.png)](https://scrutinizer-ci.com/g/flexphp/flex-skeleton-bundle)
[![License](https://poser.pugx.org/flexphp/skeleton-bundle/license)](https://packagist.org/packages/flexphp/skeleton-bundle)
[![composer.lock](https://poser.pugx.org/flexphp/skeleton-bundle/composerlock)](https://packagist.org/packages/flexphp/skeleton-bundle)

Skeleton bundle for Symfony

Change between frameworks when you need. Keep It Simple, SOLID and DRY with FlexPHP.

## Installation

Make sure Composer is installed globally, as explained in the
[installation chapter](https://getcomposer.org/doc/00-intro.md)
of the Composer documentation.

Applications that use Symfony Flex
----------------------------------

Open a command console, enter your project directory and execute:

```console
composer require skeleton-bundle
```

Applications that don't use Symfony Flex
----------------------------------------

### Step 1: Download the Bundle

Open a command console, enter your project directory and execute the
following command to download the latest stable version of this bundle:

```console
composer require skeleton-bundle
```

### Step 2: Enable the Bundle

Then, enable the bundle by adding it to the list of registered bundles
in the `config/bundles.php` file of your project:

```php
// config/bundles.php

return [
    // ...
    FlexPHP\Bundle\FlexPHPSkeletonBundle::class => ['all' => true],
];
```

## License

Skeleton-bundle is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
