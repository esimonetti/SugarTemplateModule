# SugarTemplateModule
Sugar template blank module leveraging composer library https://packagist.org/packages/esimonetti/sugar-module-packager

## How to create a new installable module
* `git clone https://github.com/esimonetti/SugarTemplateModule.git <module name>`
* `cd <module name>`
* `composer install`
* Add code and configuration changes
* `./vendor/bin/package <version number>`
* Install generated zip package into Sugar instance
