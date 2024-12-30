To create a project:
---------------------- 
    $ composer create-project laravel/laravel <projectName>

To Create a controller:
-------------------------
    $   php artisan make:controller <ControllerName>

To create a middleware:
-------------------------
    $  php artisan make:middleware <MiddlewareName>
Note: after creating a middleware you should add it in the kernel.php

To create a policy:
-------------------
    $ php artisan make:policy <PolicyName> --model=<AssociatedModelName>
Note: After creating a policy we should add those in the ***AuthServiceProvider.php***, the block name is ***$policies***

To run the  migration file:
---------------------------
    $ php artisan migrate

To remove all the table and re-run the all migration
----------------------------------------------------
    $ php artisan migrate:fresh

To create a migration for create a table:
-----------------------------------------
    $ php artisan make:migration <migration_file_name>

To create a migration file for update the table ddl:
----------------------------------------------------
    $ php artisan make:migration <name_of_migration_file> --table=<tableName>

To resize the image:
--------------------
    $ composer require intervention/image

For search operation
--------------------
    $ composer require laravel/scout

#### To use this library
    $  php artisan vendor:publish --provider="Laravel\Scout\ScoutServiceProvider"

 
