# Setup New Mac

## Install OSX

## Copy .ssh folder from dropbox to copy 

Download backed up .ssh folder and place in ~/

### Sublime Text

Download Sublime Text http://www.sublimetext.com/3

Install Sublime Text Package Manager https://packagecontrol.io/installation

Restart Sublime

Use package control to install Themr (cmd+shift+p) and type install - select install package, then search for Themr - press enter.

Install Material theme in the same way - https://github.com/equinusocio/material-theme

cmd+shift+p - Themr - select themes - select material theme, restart Sublime.

### Install Virtual Box

### Install Vagrant

### Install Command Line Tools
type 'git' in terminal to do this and hit enter

### Install Homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### Laravel
#### Install Homestead
configure path in ~/.homstead.yaml

### Install composer
curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

Add composer to your PATH variable:
in ~/
vi .bash_profile

#### Install Sequel Pro


# Mac OS X Dev Setup

This document describes how I set up my developer environment on a new MacBook or iMac. We will set up [Node](http://nodejs.org/) (JavaScript), [Python](http://www.python.org/), and [Ruby](http://www.ruby-lang.org/) environments, mainly for JavaScript and Python development. Even if you don't program in all three, it is good to have them as many command-line tools use one of them. As you read  and follow these steps, feel free to send me any feedback or comments you may have.

The document assumes you are new to Mac. The steps below were tested on **OS X Mountain Lion**.

If you have any comments or suggestions, feel free to give me a shout [on Twitter](https://twitter.com/nicolahery)!

- [System update](#system-update)
- [System preferences](#system-preferences)
- [Google Chrome](#google-chrome)
- [iTerm2](#iterm2)
- [Homebrew](#homebrew)
- [Consolas](#consolas)
- [Beautiful terminal](#beautiful-terminal)
- [iTerm2](#iterm2)
- [Git](#git)
- [Sublime Text](#sublime-text)
- [Vim](#vim)
- [Python](#python)
- [Virtualenv](#virtualenv)
- [IPython](#ipython)
- [Numpy and Scipy](#numpy-and-scipy)
- [MySQL](#mysql)
- [Node.js](#nodejs)
- [JSHint](#jshint)
- [Ruby and RVM](#ruby-and-rvm)
- [LESS](#less)
- [Heroku](#heroku)
- [MongoDB](#mongodb)
- [Redis](#redis)
- [Elasticsearch](#elasticsearch)
- [Projects folder](#projects-folder)
- [Apps](#apps)