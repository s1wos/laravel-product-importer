# laravel-product-importer

<!--Установка-->
1) git clone https://github.com/s1wos/laravel-product-importer.git
2) cd laravel-product-importer
3) composer install
4) php artisan migrate
5) Скопируйте файл .env.example в .env и настройте параметры базы данных

          DB_CONNECTION=mysql
          DB_HOST=127.0.0.1
          DB_PORT=3306
          DB_DATABASE=your_database_name
          DB_USERNAME=your_username
          DB_PASSWORD=your_password

7) php artisan migrate
8) php artisan serve

Тестирование: 
php artisan test
   
