# Oseille-Db

PHP Database abstraction layer.

*Note: I use this package for my own projects, it contains only the features I need.*

## 1. Installation and Autoloading

This package requires PHP 5.6. For specifics, please examine the package [composer.json](https://github.com/oseille/Db/blob/master/composer.json) file.

You may check if your PHP and extension versions match the platform requirements using `composer diagnose` and `composer check-platform-reqs`. (This requires [Composer](https://getcomposer.org/) to be available as composer.)

This package is installable and PSR-4 autoloadable via [Composer](https://getcomposer.org/) as oseille/db. For no dev, use `composer install --no-dev` and for dev, use `composer install`.

Alternatively, [download a release](https://github.com/oseille/Db/releases), or clone this repository, then map the Oseille\Db\ namespace to the package src/ directory.

## 2. Documentation

I wrote and I use this package for my own projects. And, unfortunately, I do not provide exhaustive documentation. Please read the code and the comments ;)

You can generate documentation using phpdocumentor. It should be installed with [Composer](https://getcomposer.org/).

## 3. Test

You should have a mysql database running somewhere to test the mysql driver connection. Use the sql file './data/schema.sql' to create the test schema and the users. Then open './tests/config/config.php' to change the ip address and port of the server.

To run the unit tests at the command line, issue `composer install` and then `./vendor/bin/phpunit` at the package root. (This requires [Composer](https://getcomposer.org/) to be available as composer.)

## 4. Contributing

Thanks you for taking the time to contribute. Please fork the repository and make changes as you'd like.

As I use this package for my own projects, it contains only the features I need. But If you have any ideas, just open an [issue](https://github.com/oseille/Db/issues/new) and tell me what you think. Pull requests are also warmly welcome.

If you encounter any **bugs**, please open an [issue](https://github.com/oseille/Db/issues/new).

Be sure to include a title and clear description,as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

## 5. License

This project is open-source and is licensed under the [MIT License](https://github.com/oseille/Db/blob/master/LICENSE).
