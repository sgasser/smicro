# symfony-micro
Symfony micro application ready for heroku

# What's included
 - Symfony 3.2
 
# Usage

## Create project

```
composer create-project sgasser/symfony-micro:dev-master
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
