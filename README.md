# RPG system boilerplate

## Background
Due to having to create several different PHP-based projects that had common (rather low) requirements, I created this boilerplate to serve as their base.

*Caution:* This project is *not* designed for use beyond my projects, therefore it is not optimised, safely configured, cleaned or well-designed. You use it at your own peril. That being said, I hope someone will find it useful for their own purposes.

## Installation guide
1. Clone the repo to desired directory
1. In no particular order:
    * adapt namespaces
    * add needed modules to composer.json
1. Run `composer install`
1. Adjust config files, in particular create `epic.php` and `deployment.php` from `*.php.example` files
1. Enjoy the simple system, ready for use.
