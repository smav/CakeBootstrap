CakeBootstrap
=============

CakePHP 2.x Twitter Bootstrap (v2.3.1) Plugin

All the files required to use Bootstrap with CakePHP, and bake Bootstrap
ready views.

A merging of the ideas and code presented in
[CakePHP-Bootstrap-Plugin](https://github.com/chronon/CakePHP-Bootstrap-Plugin)
and [cakeStrap](https://github.com/Rhym/cakeStrap) for my convenience.

Installation:
-------------

```sh
git clone git@github.com:smav/CakeBootstrap APP/Plugin/CakeBootstrap
```

Basic Usage:
-----

In `Config/bootstrap.php`:

```php
CakePlugin::loadAll(array(
	'CakeBootstrap'
));
```

In the layout:

```php
echo $this->Html->css(array(
	'CakeBootstrap.bootstrap.min.css',
	'CakeBootstrap.bootstrap-responsive.min.css'
));
```

```php
echo $this->Html->script(array(
	'//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js',
	'CakeBootstrap.bootstrap.min.js'
));
```

View/Template Baking:
-----

[Cake Bake
Docs](http://book.cakephp.org/2.0/en/console-and-shells/code-generation-with-bake.html)

```sh
```
