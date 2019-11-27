# coding-standard
PHP CodeSniffer Coding Standard

## Installation
This standard can be installed with the [Composer](https://getcomposer.org/) dependency manager.

1. [Install Composer](https://getcomposer.org/doc/00-intro.md)

2. Install the coding standard as a dependency of your project

        composer require --dev free2er/coding-standard

3. Create phpcs configuration

        cp vendor/free2er/coding-standard/phpcs.xml.dist .
        nano phpcs.xml.dist

4. Done!

        vendor/bin/phpcs
