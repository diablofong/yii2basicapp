yii2basicapp Application Template
================================

yii2basicapp  application Template is base on Yii 2 Basic Application Template.

The Template Composer (json file) add Three 3rd-party packages : kartik-v/yii2-grid , kartik-v/yii2-detail-view , kartik-v/yii2-icons

The template contains the basic features including user login/logout and a contact page.
It includes all commonly used configurations that would allow you to focus on adding new
features to your application.


DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources



REQUIREMENTS
------------

The minimum requirement by this application template that your Web server supports PHP 5.4.0.


INSTALLATION
------------

### Install from an Archive File

Extract the archive file downloaded from [github](https://github.com/diablofong/yii2basicapp) to
a directory named `your project name` that is directly under the Web root.

You can then access the application through the following URL:

1. open terminal to your project path

2. inpust the `sudo composer install`

Now you should be able to access the application through the following URL, assuming `your project name` is the directory
directly under the Web root.

~~~
http://localhost/your project name/web/
~~~


CONFIGURATION
-------------

### Database

Edit the file `config/db.php` with real data, for example:

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=yii2basic',
    'username' => 'root',
    'password' => '1234',
    'charset' => 'utf8',
];
```

**NOTE:** Yii won't create the database for you, this has to be done manually before you can access it.

Also check and edit the other files in the `config/` directory to customize your application.
