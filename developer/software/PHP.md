#PHP

[PHP API](http://php.net/manual/en/index.php) [HHVM Document](http://docs.hhvm.com/)

PHP is a server-side scripting language designed for web development.
It is widely used in web development.

In Elearn Server, php-cli is provided for some basic usage.
The php engine for production usage is the [HHVM](http://hhvm.com/).
The current version is 3.9.1~trusty (LTR).
For installation, please refers to [here](https://github.com/facebook/hhvm/wiki/Prebuilt-packages-on-Ubuntu-14.04)

[hphpiz](https://github.com/facebook/hhvm/tree/master/hphp/tools/hphpize) is required for building special extension.

To install please run:

````
sudo apt-get install -y hhvm-dev
````

Here is the list of extension:

- [Mongofill](https://github.com/mongofill/mongofill-hhvm)
