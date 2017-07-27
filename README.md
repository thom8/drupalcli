thom8/drupalci [![CircleCI](https://circleci.com/gh/thom8/drupalcli.svg?style=svg)](https://circleci.com/gh/thom8/drupalcli)
==========

This is a composer meta package for installing [Drush](http://www.drush.org/en/master/) and [Drupal console](https://drupalconsole.com/) in a single project.

# Why?

This project will attempt to control dependency conflicts which will allow Drush and Console developers to update their projects without the burden of testing compatibility. 


# Installation

```bash
composer require thom8/drupalcli
```

# Updating

```bash
composer update thom8/drupalcli --with-dependencies
```
