# About

BlaBlaCar free alternative written in Laravel (PHP+MySQL). This is web version.

## Live site

https://yugoauto.com

# Used components

## Tailwindcss components

https://flowbite.com/docs/components/tables/

## Auto complete

Used for auto complete for cities

https://jqueryui.com/autocomplete/#custom-data

## Datetime picker

Used for time picker

https://github.com/xdan/datetimepicker

## Cookie consent

https://cookieconsent.popupsmart.com/gdpr-cookie-consent/

## Toastr

Used for showing notifications

https://github.com/CodeSeven/toastr

# Tech

## Deployment script

``` 
git reset
git checkout .
git checkout master
git pull --rebase
composer install --no-dev
php artisan migrate --force
npm i
npm run build

php artisan optimize:clear
php artisan route:cache
php artisan config:cache
php artisan view:cache
```

# Server config

## File upload

In order to be able to upload a file enable: highlight_file() and tmpfile().
