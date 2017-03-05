# symfony seed
This is a pre configured Symfony project, with common Bundles like:
  - FOSUserBundle
  - SonataAdminBundle
  - FOSOAuthServerBundle
  - FOSRestBundle
  - NelmioCorsBundle
  - NelmioApiDocBundle

# prerequisites
Before start you must have installed:
  - git
  - php
  - composer
  - phpunit

## installing
clone the project
```sh
git clone http://bitckucet.adsa.co/symfony-seed.git
```

install the vendors
```sh
composer install
```

create the database
```sh
php bin/console doctrine:schema:create
```
run the project
```sh
php bin/console server:run
```
