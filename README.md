# Ansible Role: Microsoft Azure CLI
[![Build Status](https://travis-ci.org/rdonkin/ansible-role-azure-cli.svg?branch=master)](https://travis-ci.org/rdonkin/ansible-role-azure-cli)

This role installs the Microsoft Azure CLI for Linux using Yum or APT, for RHEL, CentOS, Debian and Ubuntu.

## Requirements

None.

## Role Variables

Sane and opinionated defaults have been provided for creating Yum and APT repositories. See `defaults/main.yml` for more information.

## Dependencies

None.

## Sample Playbook
```
- hosts: all

  roles:
    - rdonkin.azure-cli
```
