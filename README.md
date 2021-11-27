# wordpress-with-composer
>Integrating WordPress with Composer

#### Well, 
- intro to Composer 
- Retrofilling a Legacy Project
- Composer concepts
- Custom installers
- Integrating Wordpress
- Managing plugins

> Composer is a tool for dependency manager PHP.
> It allows us to declare the dependent librariess the project needs and installs them in the projects for them. 
> [composer](https://getcomposer.org/)


Install Composer - [Windows](https://getcomposer.org/doc/00-intro.md#installation-windows)


Check if you have composer installed or not

In cmd.  
> `composer -V ` or `composer -v` or `composer`


Create a folder e.g. composer-example

Open the folder in your code editor like VSCode

In the terminal (in the folder e.g. composer-example, run
 
> composer install

- it won't install because couldn't find composer.json
- Create composer.json file in the folder
- paste  `{
    "require": {
        "monolog/monolog": "2.0.*"
    }
}`  and save the file.

> composer install







