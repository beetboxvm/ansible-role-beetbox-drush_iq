Drush Issue Queue Commands
=========

Drush issue queue commands makes it much easier for beginners, and much faster for beginning and experienced git users alike to create and apply patches.

Requirements
------------

This role is specifically developed as an extension to beetbox but should be generic enough to use in other projects -- https://github.com/drupalmel/beetbox

## Role Variables

Available variables are listed below, along with default values:

Drush configuration directory.

    drush_home

# beetbox

https://github.com/beetboxvm/beetbox

## Requirements

* [Vagrant](https://www.vagrantup.com/) >= 1.8
* [Virtualbox](https://www.virtualbox.org/)
* [Vagrant Hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)
* [Vagrant Auto-network](https://github.com/oscar-stack/vagrant-auto_network)

## Quickstart

  1. Open terminal (or [git bash](https://msysgit.github.io/) for windows users) and run the following commands --

  ```
  git clone https://github.com/beetboxvm/ansible-role-beetbox-symfony.git symfony && cd $_
  vagrant up
  ```

  2. Go to http://symfony.local/

  ```
  username: admin
  password: admin
  ```

## License

MIT
