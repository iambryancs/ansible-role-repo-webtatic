# Ansible Role: Webtatic Repository

[![Build Status](https://travis-ci.org/iambryancs/ansible-role-repo-webtatic.svg?branch=master)](https://travis-ci.org/iambryancs/ansible-role-repo-webtatic)

Installs the [Webtatic](https://webtatic.com/projects/yum-repository/) repository on RHEL/CentOS

## Requirements
Make sure you are running this on RHEL/CentOS

## Dependencies
- [geerlingguy.repo-epel](https://github.com/geerlingguy/ansible-role-repo-epel)

## How to use
* Include `iambryancs.repo-webtatic` in your requirements.yml
```yml
#requirements.yml
---
- src: iambryancs.repo-webtatic
```
* Install the role by running `ansible-galaxy install -r path/to/your/requirements.yml`

## Example Playbook
```yml
- hosts: all
  roles: 
    - iambryancs.repo-webtatic
```
## License
MIT
