# Laravel Pembayaran Listrik UKK

Repository ini merupakan proyek Laravel untuk aplikasi pembayaran listrik sebagai bagian dari tugas UKK (Ujian Kompetensi Kejuruan).

## Membuat Project:
```bash 
   composer create-project laravel/laravel pembayaran-listrik-ukk
```

## Git:
```bash 
   buat repository
   git config --global user.name "Ilham"
   git config --global user.email "admin@gmail.com"
   git init
   git remote add origin https://github.com/k4ilham/pembayaran-listrik-ukk.git
   git add .
   git commit -m "Sail & Filamen"
   git push --set-upstream origin master
   git add .
   git commit -m "readme"
   git push --set-upstream origin master
```
## Instalasi Laravel Sail:
```bash 
   composer require laravel/sail --dev
   php artisan sail:install
   alias sail='bash vendor/bin/sail'
   chmod +x vendor/laravel/sail/bin/sail
   sail up -d
   sail artisan optimize
```

## Instalasi Laravel Filamen:
```bash 
    composer require filament/filament:"^3.0-stable" -W
    sail artisan filament:install --panels
    sail artisan migrate
    sail artisan make:filament-user
```
   buka web di browser

```bash 
    http://localhost/admin/login
    username & email : admin@gmail.com
    password : 12345678
```

