# Vagrant-Debian-8-Box
A Debain 8 RC1 amd64 netboot VirtualBox Box for Vagrant

This repo contain definition files to build a
[Vagrant](http://www.vagrantup.com) box based on the Debian Jessie RC1 amd64 netboot
iso images.

##Originals
https://github.com/jedi4ever/veewee/tree/master/templates/Debian-7.6.0-amd64-netboot

https://github.com/holms/vagrant-jessie-box


##Dependencies

You need to install [Vagrant](http://www.vagrantup.com), [VirtualBox](https://www.virtualbox.org/) and
[veewee](https://github.com/jedi4ever/veewee) with your favorite package
manager to build the image.

##Building

Just run the following command in the repository root:

    $ veewee vbox build Debian-8.RC1-amd64-netboot
    $ veewee vbox export Debian-8.RC1-amd64-netboot
