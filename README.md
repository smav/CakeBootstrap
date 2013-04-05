CakeBootstrap
=============

CakePHP 2.x (2.3.1) Twitte Bootstrap(2.3.1) Plugin

All the files required to use Bootstrap with CakePHP v2, and bake templates to
generate Bootstrap ready views.

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
	'Bootstrap'
));
```

In the layout:

```php
echo $this->Html->css(array(
	'Bootstrap.bootstrap.min.css',
	'Bootstrap.bootstrap-responsive.min.css'
));
```

```php
echo $this->Html->script(array(
	'//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js',
	'Bootstrap.bootstrap.min.js'
));
```

Baking:
-----
