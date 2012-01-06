Introduction
============

This [Archlinux](http://www.archlinux.org) package contains a script allowing minimal configuration of an
Archlinux system for running in the Amazon Web Services Elastic Computing Cloud (EC2).

Basically, the script does the following:

* Associate the hostname and the IP address of the instance in the /etc/hosts file
* Allow the public key specified as the instance start parameter to log in as root
* Creates a basic user named arch if it does not exist
* On first boot, run as a script the metadata passed as a start parameter to the instance

Along with [linux-ec2](http://github.com/antoinemartin/linux-ec2) and [ec2build](http://github.com/antoinemartin/ec2build),
this package allows building a basic Archlinux EC2 instance.
