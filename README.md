# Ansible role for NodeJS

[![Build Status](https://travis-ci.org/torian/ansible-role-nodejs.svg)](https://travis-ci.org/torian/ansible-role-nodejs)

## Tested On

  * Ubuntu Trusty
  * Centos 6

## Defaults

```
nodejs_version:     0.10
nodejs_npm_version: 2.11.1
```

### NodeJS versions

Tested the following versions:

  * 0.10
  * 0.12
  * 4.x

*NOTE:* Depending on the distribution's version, you may or may not
run recent nodejs versions

## Usage

```
---
- hosts: all

  vars:
    - nodejs_version: 4.x

  roles:
    - { role: ansible-role-nodejs }

# vi:ts=2:sw=2:et:ft=yaml
```

## TODO

FIXME

