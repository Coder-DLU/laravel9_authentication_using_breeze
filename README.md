# laravel9_authentication_using_breeze
## 1. Install Laravel 9
```Dockerfile
composer create-project laravel/laravel laravel9_authentication_using_breeze
```
- Install Breeze
```Dockerfile
composer require laravel/breeze --dev
```
- command chạy 
```Dockerfile
php artisan breeze:install
```
```Dockerfile
npm install && npm run dev
```
```Dockerfile
php artisan migrate
```
- Xem những tệp được tạo ra : Vào Generated Controller Files:

![Container](a.png)

Tệp router đã tạo:

![Container](a1.png)

 Blade Files:
 
 ![Container](a2.png)
 
 ## 2.Run Laravel App:
 ```Dockerfile
php artisan serve
```
- Vào http://localhost:8000/

 ![Container](a3.png)
 ![Container](a4.png)
 ![Container](a5.png)
 ![Container](a6.png)
