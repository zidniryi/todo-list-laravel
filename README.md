# Laravel Todo List Post App

Laravel to list app

## Installation

```bash
git clone https://github.com/zidniryi/todo-list-laravel.git
git checkout zidni/feature
git pull
cp .env.example .env
composer install
php artisan key:generate
php artisan serve

```
### note
make sure you already import the db ini folder : **sql database/db_kuliah2.sql**

### env stuff
Edit like bellow in env

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_kuliah2
DB_USERNAME=root
DB_PASSWORD=
```

### url (based on your port)
http://127.0.0.1:8001/posts
