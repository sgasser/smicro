# symfony-micro
Symfony micro application ready for heroku

[![Packagist](https://img.shields.io/packagist/v/sgasser/symfony-micro.svg)](https://packagist.org/packages/sgasser/symfony-micro)
[![Installs](https://img.shields.io/packagist/dt/sgasser/symfony-micro.svg)](https://packagist.org/packages/sgasser/symfony-micro)
[![license](https://img.shields.io/github/license/sgasser/symfony-micro.svg)]
(https://github.com/sgasser/symfony-micro/blob/master/LICENSE)

# What's included
 - Symfony 3.2
 
# Usage

## Create project

```
composer create-project sgasser/symfony-micro
```

## Start local server

```
php bin/console server:run
```

## Deploy to heroku

Visit http://heroku.com/ to set up an account.

Initialize local GIT
```
git init
git add .
git commit -m 'Initial commit'
```

Create heroku app
```
heroku create
```

Set config
```
heroku config:set SYMFONY_ENV=prod
```

Push
```
git push heroku master
```

Open app
```
heroku open
```
