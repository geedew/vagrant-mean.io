Role Name
========

This is meant to be a simple, quick way to get a fully operational server with Ubuntu/Vagrant running a MEAN stack [Mongo,Express,Angular,Node].

It essentially trying to make http://mean.io automated.

Installation
------------
# Status
** Not fully baked **


# Installing

- Install Virtualbox (https://www.virtualbox.org/wiki/Downloads)
- Install Vagrant (http://www.vagrantup.com/downloads.html)
- Install Ansible (via brew on OSX http://brew.sh/ )
```sh
$> brew install ansible
```
- Pull this repo
```sh
$> git clone git@github.com:geedew/vagrant-mean.io.git
```
- Edit any of the files to customize (still a little hardcoded in places)
- Run Vagrant
```sh
$> vagrant up
```

You can then login and run the command `grunt` from the `/home/vagrant/mean/` directory.

Requirements
------------

- Virtualbox 4.2+
- Vagrant 1.3.5+
- Ansible


License
-------

MIT 2014

Author Information
------------------

Drew Wilson <drew@geedew.com>
