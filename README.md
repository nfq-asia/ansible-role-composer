## Ansible Role Composer for PHP

### A. Purpose

The task is to write an Ansible role to install and manage composer stable version (from 1.8.4)

### B. Specifications

1. Input
    - Composer version: 1.8.4
    - Composer install path: `/usr/local/bin`

2. Prerequisites
    - Php is requirement.
    - An EC2 instance with a static IP mapped to a hostname

3. Output
    - A standard composer command for PHP applications

---
### Defaults

*   `composer_version` - version of composer, default is `1.8.4`.
*   `composer_path` - dir path that used to install composer, default is `/usr/local/bin`.

### Required variables
### Optional variables
### Tags

*   `install` - install composer.
### Notes

*   This role requires php to run.
