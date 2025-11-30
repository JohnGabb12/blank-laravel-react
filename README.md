# Blank Laravel Breeze + React + Inertia
This project is a blank Laravel Breeze + React + Inertia project.
This project has no pages, hooks, components and tailwind colors while still having the dependencies of a laravel breeze.


# Startup
Clone the project
```bash
git clone https://github.com/JohnGabb12/blank-laravel-react
```

Install dependencies
```bash
composer install
npm install
```

Migrate the database
```bash
php artisan migrate --seed
```

Copy the env file
```bash
copy .env.example .env
```

Generate the key and wayfinder
```bash
php artisan key:generate
php artisan wayfinder:generate
```
