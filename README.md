Continuous Delivery
==========================

This is the associate files that I'm using for my talk at [progressive.net 2014](https://skillsmatter.com/conferences/1820-progressive-dot-net-tutorials-2014). You'll need to be there in person to get a copy of the VMs I'll be using.

## Prerequistes

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](http://www.vagrantup.com/)

## Download boxes from the network

It's 12 GB =( but it's all setup for you

Download VMs locally from

\\192.168.1.100\public\vagrant\

Then register the boxes with vagrant

vagrant box add file://<somewhere>/Vagrant/windows.teamcity/winteamcity64_011_virtualbox.box --name=prognet/winteamcity

vagrant box add file://<somewhere>/windows.web/wintweb_010_virtualbox.box --name=prognet/winweb

### then

in this project folder

cd teamcity

vagrant up
