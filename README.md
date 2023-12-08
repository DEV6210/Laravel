# Laravel

# how to reate laravel project?
composer create-project laravel/laravel example-app

# how tostart Laravel's local development server?
php artisan serve

# how to make basic controller
php artisan make:controller controller-name

# how to make single controller
php artisan make:controller controller-name --invokable

# how to make resource controller
php artisan make:controller controller-name --resource

# Action Handle by resource controller
![Screenshot (41)](https://github.com/DEV6210/Laravel/assets/91625966/ab605486-7027-4036-baab-0718e3b56f16)

# how to make components
php artisan make:component input


# --------------------------------------
# how to migrate database
php artisan migrate
 # how to create table
 php artisan make:migration create_users_table

 # delete all table and re generate
 php artisan make:refresh

 # delete all table and re generate
 php artisan make:rollback

# Add column
 php artisan make:migration add_colName_to_tableName_table
after define column-> # php artisan migrate 


# --------------------------------------
# how to create model
 php artisan make:model databasename
