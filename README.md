<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [ansible-apt-sources](#ansible-apt-sources)
  - [Build status](#build-status)
  - [Role info](#role-info)
  - [Role purpose](#role-purpose)
  - [Requirements](#requirements)
  - [Role Variables](#role-variables)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# ansible-apt-sources

## Build status

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-apt-sources.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-apt-sources)

## Role info

An [Ansible](https://www.ansible.com) role to configure `/etc/apt/sources.list`
on `Debian/Ubuntu` systems.

## Role purpose

The purpose of this role is to configure systems `/etc/apt/sources.list`
consistently or independently.

> NOTE: This role is **not** intended to manage repositories other than the
> distribution sources.

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
---
- hosts: all
  vars:
  roles:
    - role: ansible-apt-sources
  tasks:
```

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
