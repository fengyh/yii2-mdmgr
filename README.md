Markdown manager with creating, editing, view etc. features
===========================================================
An Yii2 extension, has a markdown editor supported by CKEditor, stores article in db, one can create, edit, view and search the articles by using this extension.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist fengyh/yii2-mdmgr "*"
```

or add

```
"fengyh/yii2-mdmgr": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

#### Application configuration

```php
'modules' => [
    ...
	'manual' => [
        'class'  => 'fengyh\mdmgr\Module',
    ],
    ...
],
```

#### Show UI

Route `/manual`  shows the user interface.

