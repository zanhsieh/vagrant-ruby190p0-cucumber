vagrant-ruby190p0-cucumber
==========================

Vagrant Ruby 1.9.0p0 Cucumber Rspec stack installed via Chef; based on [GoRails](https://gorails.com/guides/using-vagrant-for-rails-development) installation guide.

Environment
===========
This mainly target Ubuntu 12.04 LTS x64 with VirtualBox and Vagrant pre-installed:

1. [Install Vagrant](http://www.vagrantup.com/downloads.html)
1. [Install VirtualBox](https://www.virtualbox.org/wiki/Downloads)

After installed, you need to install two plugins for Vagrant:

- vagrant-vguest
- vagrant-librarian-chef

So:

    $ vagrant plugin install vagrant-vbguest
    $ vagrant plugin install vagrant-librarian-chef


Chef Recipes Used
=================
- apt
- build-essential
- nodejs
- ruby\_build
- rbenv
- vim
- mysql


Ruby And Gems Installed Via rbenv
=================================
- ruby 1.9.3-p0
- bundler
- rake
- cucumber
- rspec-expectations
