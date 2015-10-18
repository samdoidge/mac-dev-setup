# New Mac Setup

My development setup on a fresh OS X install. For PHP development with Laravel framework using Homestead setup on Vagrant.

- [Private Key](#private-key)
- [Sublime Text](#sublime-text)
- [Virtual Box](#virtual-box)
- [Vagrant](#vagrant)
- [Command Line Tools](#command-line-tools)
- [Homebrew](#homebrew)
- [Composer](#composer)
- [Homestead](#homestead)
- [Laravel](#laravel)
- [Sequel Pro](#sequel-pro)

## Private key

Download backed up .ssh folder from Dropbox and place in home folder (~/)

## Sublime Text

Download Sublime Text http://www.sublimetext.com/3

Install Sublime Text Package Manager https://packagecontrol.io/installation

Restart Sublime

Use package control to install Themr (cmd+shift+p) and type install - select install package, then search for Themr - press enter.

Install Material theme in the same way - https://github.com/equinusocio/material-theme

cmd+shift+p - Themr - select themes - select material theme, restart Sublime.

## Virtual Box

Search and download Virtual Box for Mac

## Vagrant

Search and download Vagrant for Mac

## Command Line Tools
type 'git' in terminal to do this and hit enter - you will be promted to install X Code command line tools - do so

## Homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

##Install composer
curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

## Homestead
Following instructions on Laravel Homestead pages
configure path in ~/.homstead.yaml

## Laravel
Use the composer install command - check laravel website.

Add composer to your PATH variable:
in ~/
vi .bash_profile

## Install Sequel Pro
Google and download

If you have any comments or suggestions, feel free to give me a shout [on Twitter](https://twitter.com/samdoidge)!