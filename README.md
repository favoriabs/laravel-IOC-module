#Laravel-IOC-Module
Laravel made available the IoC container for developers. This bash script is aimed at speeding up development for Laravel developers.

## How to use
Add the file to the root of your Laravel project directory and  run it this way: **./ioc.sh**

## What it does
After running the bash script, you will be prompted for a module name. After that input, the following is performed as a result of that:
- A Laravel model is created in the **app** directory.
- A migration file is created with the module name in **database/migrations**.
- A Service provider is created in **app/Providers** and registered inside **config/app.php** under the **providers** section.
- A Laravel Controller is created for you in **app/Http/Controllers**.
- A Repositories directory which houses your repository files is created in the **app** directory.
- A Repository and Contract file is created inside **app/Repositories/module_name** directory.
- Your repository and contract files are bound inside the respective Service Providers.

## Contributors
[Eric Renouf](http://stackoverflow.com/users/4687135/eric-renouf/) on [Stackoverflow](http://stackoverflow.com/)

> *Made with love from [nHub Nigeria](http://nhubnigeria.com/)*