# backend-enginer-binar

langkah instalasi :
1. git clone git@github.com:wahyuwehaye/backend-enginer-binar.git
2. cd soal-no-3
3. database setting :
      DB_CONNECTION=mysql
      DB_HOST=127.0.0.1
      DB_PORT=3306
      DB_DATABASE=testbinar
      DB_USERNAME=root
      DB_PASSWORD=
4. composer require laravel/passport
5. php artisan migrate
6. php artisan passport:install
7. php artisan serve
8. API :
      - register : http://localhost:8000/api/register
      - login : http://localhost:8000/api/login
      - create : http://localhost:8000/api/posts
      - show : http://localhost:8000/api/posts
      - show by id :  http://localhost:8000/api/posts/{id}
      - update : http://localhost:8000/api/posts/{id}
      - delete : http://localhost:8000/api/posts/{id}
