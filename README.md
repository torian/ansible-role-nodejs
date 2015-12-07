# Ansible role for NodeJS

[![Build Status](https://travis-ci.org/torian/ansible-role-nodejs.svg)](https://travis-ci.org/torian/ansible-role-nodejs)

## Defaults

```
nodejs_version:     '0.10'
nodejs_npm_version: '2.11.1'
```

## Usage

```
---
- hosts: all

  vars:
    - nodejs_version: 4.2

  roles:
    - { role: torian.nodejs }

```

## TODO

FIXME

