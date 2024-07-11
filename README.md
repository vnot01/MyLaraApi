<p align="center"><a href="LARAVEL.md" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

### HOW to Use
- Download Install ([how to Git Instalation](https://git-scm.com/)):
    - Windows:
        * winget ([how to instalation](https://learn.microsoft.com/en-us/windows/package-manager/winget/#install-winget))
            ```sh
            winget install --id Git.Git -e --source winget
            ```
    - OSX:
        * brew ([how to instalation](https://brew.sh/))
            ```sh
            brew install git
            ```
- Open Terminal / Command Prompt (CMD):
    * Clone GIT File:
        ```sh
        git clone https://github.com/vnot01/MyLaraApi.git
        ```
    * Go to Clone Folder:
        ```sh
        cd MyLaraAPI
        ```
- Install All Component:
    * composer ([how to instalation](https://getcomposer.org/download/)):
        ```sh
        composer install
        ```
- Copy **.env** from **.env.example**:
    * cp / copy:
        ```sh
        cp .env.example .env
        ```
- Create Key of Laravel:
    * php:
        ```sh
        php artisan key:generate
        ```
- Edit your **DB Connection** to **sqlite** and give "**#**" to the others (make Comment) in **.env**:
    * .env:
        ```sh
        DB_CONNECTION=sqlite
        # DB_HOST=127.0.0.1
        # DB_PORT=3306
        # DB_DATABASE=laravel
        # DB_USERNAME=root
        # DB_PASSWORD=
        ```
- Make Migration of Database using migrate Command:
    * php:
        ```sh
        php artisan migrate
        ``` 
- Choose **YES** to Create IT
![Migration Database SQLite](/assets-md/migrate-ss.png)

- Install Extension REST Cient:
**Extension ID (Visual Studio Code [how to VS Code Instalation](https://code.visualstudio.com/))**
    * Extension ID:
        ```sh
        humao.rest-client
        ``` 
![Extension REST Cient](/assets-md/extension-ss.png)

- Run your Apps:
    * php:
        ```sh
        php artisan serve
        ``` 
- Test Your API:
Using test.http
