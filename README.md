# Flag-icon Bundle for Symfony 4.0

## Installation

### Add bundle to your composer.json file

``` js
// composer.json

{
    "require": {
		// ...
        "btc/flagicon-bundle": "^1.0"
    }
}
```

### Add bundle to your application

``` php
// config/bundles.php

return [
    // ...
    BTC\FlagIconBundle\BTCFlagIconBundle::class => ['all' => true],
    // ...
];
```

### Download the bundle using Composer

``` bash
$ composer require btc/flagicon-bundle
```

### Install assets

Given your server's public directory is named "public", install the public vendor resources

``` bash
$ php bin/console assets:install public
```

Optionally, use the --symlink attribute to create links rather than copies of the resources 

``` bash
$ php bin/console assets:install --symlink public
```

## Usage

Refer to the desired files in your HTML template, e.g.

``` html
<link rel="stylesheet" type="text/css" href="{{ asset('bundles/btcflagicon/css/flag-icon.min.css') }}" />
```

# Licenses

Refer to the source code of the included files for license information

# References

1. http://lipis.github.io/flag-icon-css/