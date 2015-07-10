# ansible-role-phpstorm


[![License](https://img.shields.io/badge/License-MIT%20License-blue.svg)](https://github.com/kosssi/ansible-role-phpstorm/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/kosssi/ansible-role-phpstorm.svg?branch=master)](https://travis-ci.org/kosssi/ansible-role-phpstorm)

Ansible role to install [phpStorm](http://www.jetbrains.com/phpstorm/).

## Role Defaults Variables

    phpstorm_version: 9.0
    phpstorm_install_dir: /opt
    phpstorm_bin: /usr/local/bin/phpstorm

## Example Playbook

    roles:
      - { role: kosssi.phpstorm, tags: phpstorm }

## Vagrant

If you have vagrant, you can test this role:

    cd tests
    vagrant up
