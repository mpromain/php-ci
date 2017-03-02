PHP CI Docker image
===================

Contains:
* Version control systems
 * GIT
 * Subversion
 * Mercurial
* PHP with extensions:
 * cgi
 * cli
 * common
 * curl
 * fpm
 * gd
 * imagick
 * interbase
 * json
 * mbstring
 * mysql
 * readline
 * redis
 * sqlite
 * phpdbg
 * xdebug (disabled - use php.ini for enable)
 * xsl
 * zip
* Composer with global packages:
 * phpunit/phpunit
 * nette/tester
 * mockery/mockery
 * jakub-onderka/php-parallel-lint
 * jakub-onderka/php-console-highlighter
 * phpstan/phpstan


Use image
=========

```
docker run -it mpromain/php-ci:7.0
```