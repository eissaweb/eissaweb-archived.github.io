---
layout: post
title: How to Update your Laravel 6 project to 8 - step by step
published: true
---
**You Want to upgrade your laravel project, but you don't want to waste time diggin through the documentation, then this article is for you.**

![](https://laravel.com/img/logotype.min.svg)

First we need to upgrade to laravel 7, then to laravel 8.

### Upgrading to laravel 7:-

1. First you need to change your PHP version to [at least 7.2.5](https://www.digitalocean.com/community/questions/how-to-upgrade-php-7-0-33-to-7-4-7-on-ubuntu-16-04-nginx).

1. Update the following dependencies in your composer.json file:
	```
    laravel/framework to ^7.0 
	nunomaduro/collision to ^4.1
	phpunit/phpunit to ^8.5
	laravel/tinker to ^2.0
	facade/ignition to ^2.0
    ```
    Basically go to coomposer.json file, and then change them like this:
    	```
        	from: "laravel/framework": "^6.0"
            to: "laravel/framework": "^7.0"
            ```
            Do this for the all the packages above.
 
2. 