# Ansible Role: qemu-guest-agent

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.qemu-guest-agent.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.qemu-guest-agent) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-qemu-guest-agent-blue.svg)](https://galaxy.ansible.com/sbaerlocher/qemu-guest-agent)

## Description

Ansible role for installing Qemu Guest Agent on installs RHEL/CentOS.

## Installation

```bash
ansible-galaxy install sbaerlocher.qemu-guest-agent
```

## Requirements

This role requires Ansible 2.5 or higher, and platform requirements are listed
in the metadata file.

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.qemu-guest-agent
```

## Changelog

### 1.0

* initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher