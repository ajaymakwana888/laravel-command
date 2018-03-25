# laravel-commands list                                           
Installing Laravel                                                                   
  1. Via Laravel Installer :- 
     - composer global require "laravel/installer"
     - laravel new blog
  2. Via Composer Create-Project :- 
     - composer create-project --prefer-dist laravel/laravel blog

Composer :
1. composer install
2. composer update
3. composer dump-autoload [--optimize]
4. composer self-update 

Local Development Server :
  - php artisan serve

List Artisan commands :
 1. php artisan list
 2. php artisan help
 3. php artisan tinker
 4. php artisan make
 5. php artisan –version
 6. php artisan routes
 
Key generate :
  - php artisan key:generate

`php artisan make` commnd list

1. create a new middleware :
  - php artisan make:middleware CheckAge

2. create Controller :
  - php artisan make:controller PhotoController
  - php artisan make:controller PhotoController --resource (with resource module)

3. create a model :
  - php artisan make:model User
  - php artisan make:model User --migration (or -m ) (with migration)

4. migrations :
  - php artisan make:migration create_users_table
  - php artisan make:migration create_users_table --create=users
  - php artisan make:migration add_votes_to_users_table --table=users
  - php artisan migrate
  - php artisan migrate:rollback
  - php artisan migrate:rollback --step=5 
  - php artisan migrate:reset (roll back all  migrations)
  - php artisan migrate:refresh (roll back & migrate)
  - php artisan migrate:refresh --step=5
  - php artisan migrate:fresh (drop all tables)
  
5. test cases
  - php artisan make:test UserTest (Feature test cases)
  - php artisan make:test UserTest --unit (unit test cases)

6. Factory
 - php artisan make:factory PostFactory

  

                                                                                          -: Ajay Makwana

