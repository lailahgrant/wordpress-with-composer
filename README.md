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

![comp](https://user-images.githubusercontent.com/28113644/143672895-e288da5d-8eaa-4ba7-92ba-a7b26c18af2b.png)


Create a folder e.g. composer-example

Open the folder in your code editor like VSCode

In the terminal (in the folder e.g. composer-example, run
 
> composer install

- it won't install because couldn't find composer.json

![comp1](https://user-images.githubusercontent.com/28113644/143672904-b0a6b24f-bb2e-4bad-b01a-a8bf8828b503.png)

- Create composer.json file in the folder
- paste  `{
    "require": {
        "monolog/monolog": "2.0.*"
    }
}`  and save the file.

> composer install

![comp2](https://user-images.githubusercontent.com/28113644/143672914-0e4b25a5-5337-4150-a263-42ec1b772ffd.png)


