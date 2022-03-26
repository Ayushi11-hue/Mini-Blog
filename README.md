
## Steps for Installtion

```
git clone https://github.com/sanz/simple-larablog.git simple-larablog
cd simple-larablog
cp .env.example .env

// Then set database credentials in .env file

composer install
php artisan key:generate
php artisan migrate
php artisan db:seed
