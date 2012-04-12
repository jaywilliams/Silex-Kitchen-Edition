Silex - Lite Kitchen Edition
============================

This is a lite flavor of [Silex Kitchen Edition][origin]. It removes the Assetic and Translation extensions, and uses Bootstrap v2.0. The folder structure in the web/ directory has changed as well. Hopefully you'll find it helpful for your Silex based applications.

Based on: [Silex Kitchen Edition][origin]

It already embed :

* HTML5 boilerplate (http://html5boilerplate.com/)
* Twitter Bootrap v2.0 with form integration (http://twitter.github.com/bootstrap/)
* Few extensions:

    * Doctrine
    * Form
    * Session
    * SymfonyBrige
    * Twig (with debug extension)
    * UrlGenerator

Installation
------------

*  `curl -s http://getcomposer.org/installer | php`
*  `php composer.phar install`
*  edit `src/config.php`
*  `chmod 777 cache/ log/`

Start hacking in `src/controllers.php`

Help
----

* <http://silex.sensiolabs.org/documentation>

[origin]: https://github.com/lyrixx/Silex-Kitchen-Edition