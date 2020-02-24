# ansible-apt-sources

Ansible role to configure `/etc/apt/sources.list`
on `Debian/Ubuntu` systems.

## Purpose

The purpose of this role is to configure systems `/etc/apt/sources.list`
consistently or independently.

> NOTE: This role is **not** intended to manage repositories other than the
> distribution sources.

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-apt-sources/workflows/Molecule%20Test/badge.svg)

### Travis CI

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-apt-sources.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-apt-sources)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
