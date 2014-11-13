boxbilling-puphpet
==================

Boxbilling PuPHPet is a Boxbilling development environment utilize Vagrant configured through PuPHPet

## Setup 
* edit host machine `/etc/hosts` file. Add:
````` 
10.20.30.11 boxbilling.dev www.boxbilling.dev
`````

* edit `puphpet/config.yaml` synced_folder source target
* run `vagrant up`

## Environment

* PHP 5.4
* xdebug enabled (xdebug.idekey - PHPSTORM)
* Ubuntu 12.04-x64

## Issues

[Do not install PHP 5.5 and Ubuntu 12.04](http://unix.stackexchange.com/questions/96942/apache-not-starting-in-vagrant-vm)
