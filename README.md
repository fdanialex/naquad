naquad (alpha)
======

Just another web content management system.

This is just an early sketch for the code.

Below is a list of things i wish to code into this baby:
* Easy template creation (visual IDE, drag&drop)
* Very modular but unrestrictive (allow for both OOP style or procedural)
* Support for databases: mysql, postgresql, mongo, flat file etc
* No database support: using files for all the data (Eg: flat html/php files containing blog posts, products etc)
* Full caching for generated files
* Built-in: LESS to CSS compilation (use LESS instead of simple CSS)
* Try to support WordPress, Joomla, Drupal (or others) modules and themes - (experiment)
* Core modules for: Blog, Board, Shop (plus others)
* Multi-site management from one admin panel
* Admin panel should be a module
* Modules can be required by other modules for functionality (ex: auth requiers db); autoloading
* Always rewrite URLs using modrewrite, or pseudo rewrite through *index.php* as */?some-nice-url*
* Fast implementation of requested features by the community (throught modules)