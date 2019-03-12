# Ansible Role: qemu-guest-agent

[![Build Status](https://img.shields.io/travis/sbaerlocher/ansible.qemu-guest-agent.svg?branch=master&style=popout-square)](https://travis-ci.org/sbaerlocher/ansible.qemu-guest-agent) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-qemu--guest--agent-blue.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/qemu-guest-agent) [![Ansible Role](https://img.shields.io/ansible/role/d/25023.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/qemu-guest-agent)

## Description

Ansible role for installing Qemu Guest Agent on RHEL/CentOS and Debian/Ubuntu or Windows.

If you are using an older version than 0.1.149 of Virtio, then use the 1.1.3 role.

## Installation

```bash
ansible-galaxy install sbaerlocher.qemu-guest-agent
```

## Requirements

This role requires Ansible 2.5 or higher, and platform requirements are listed
in the metadata file.

## Dependencies

To install the agent for Windows, the role sbaerlocher.virtio must be installed.

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.qemu-guest-agent
```

## Changelog

### 1.2

Changing the path to the msi. 

### 1.1

* add Windows Support

### 1.0

* initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher
