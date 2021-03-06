# What's next?

## Usefull commands:

### Server commands

* `php bin/console server:run [boundIp[:port]]`: Open a server. Same as `php -S 127.0.0.1:8000 -t public`
* `php bin/console server:start [boundIp[:port]]`: Start as a service
* `php bin/console server:stop`: Stop as a service
* `npm run webpack:run:dev`: Start the assets server

### Models related

* `php bin/console make:entity Something`: create model named *Something*
* `php bin/console doctrine:migrations:diff`: Generate SQL diff for models
* `php bin/console doctrine:migrations:migrate`: Apply diff

### Translations related

* `php bin/console debug:translation fr`: show debug infos about locale *fr*
* `php bin/console translation:update --dump-messages --force fr`: refresh translation files for locale *fr*

## Links:

For MySQL connection: https://symfony.com/doc/current/doctrine.html
Read the documentation at https://symfony.com/doc

## For posterity

### Enable debugger:

1. Run `composer require symfony/web-profiler-bundle`
1. In `config/bundles.php`, ensure `Symfony\Bundle\WebProfilerBundle\WebProfilerBundle::class => ['dev' => true, 'test' => true],`

### Sample repo with Symfony4

https://github.com/liweiyi88/julianli

https://github.com/JulieAlary/symfony4Start

### Most Complete Repo AFAIK

https://github.com/matthieuleorat/documentManager

### Carousel JS with provided CDN

http://kenwheeler.github.io/slick/
