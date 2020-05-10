### Laravel/Lumen

composer create-project laravel/laravel herokularavel --prefer-dist

cd herokuLaravel

echo web: vendor/bin/heroku-php-apache2 public/ > Procfile

$ git init
$ git add .
$ git commit -m "firt commit to heroku"

heroku login

heroku create

 git push heroku master
 
$ heroku config:add APP_DEBUG=true
$ heroku config:add APP_KEY=base64:2134qb9vvuyBcXWpLThHS2aP8xyF4odhMmXqWDgYljE=

$ heroku config:add APP_NAME=Laravel
$ heroku config:add APP_ENV=production
$ heroku config:add APP_URL=https://pacific-wildwood-22940.herokuapp.com/

// Jika menggunakan PostgreSQL
$ heroku addons:create heroku-postgresql:hobby-dev//mengambil data url
$ heroku pg:credentials:url

$ heroku config:add DB_CONNECTION=pgsql
$ heroku config:add DB_HOST=ec2-174-129-252-226.compute-1.amazonaws.com
$ heroku config:add DB_PORT=5432
$ heroku config:add DB_DATABASE=d44v1r63c3rodn
$ heroku config:add DB_USERNAME=erqzihcpgieidg
$ heroku config:add DB_PASSWORD=687e60a4ed5fda2c738148f0918137979076168b537ed45b383d1bb10a242251

$ heroku run php artisan migrate

heroku open
