# [Ansible role demo](#ansible-role-demo)

Demo role

|GitHub|Issues|Pull Requests|Version|Downloads|
|------|------|-------------|-------|---------|
|[![github](https://github.com/buluma/ansible-role-demo/actions/workflows/molecule.yml/badge.svg)](https://github.com/buluma/ansible-role-demo/actions/workflows/molecule.yml)|[![Issues](https://img.shields.io/github/issues/buluma/ansible-role-demo.svg)](https://github.com/buluma/ansible-role-demo/issues/)|[![PullRequests](https://img.shields.io/github/issues-pr-closed-raw/buluma/ansible-role-demo.svg)](https://github.com/buluma/ansible-role-demo/pulls/)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-demo.svg)](https://github.com/buluma/ansible-role-demo/releases/)|[![Ansible Role](https://img.shields.io/ansible/role/d/buluma/demo)](https://galaxy.ansible.com/ui/standalone/roles/buluma/demo/documentation)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/buluma/ansible-role-demo/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- become: true
  gather_facts: true
  hosts: all
  name: Converge
  roles:
    - ansible-role-demo
```

Also see a [full explanation and example](https://buluma.github.io/how-to-use-these-roles.html) on how to use these roles.


## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-demo/blob/master/requirements.txt).


## [Context](#context)

This role is part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:

![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-demo/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/robertdebock):

|container|tags|
|---------|----|
|[EL](https://hub.docker.com/r/robertdebock/enterpriselinux)|all|

The minimum version of Ansible required is 2.12, tests have been done on:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them on [GitHub](https://github.com/buluma/ansible-role-demo/issues).

## [License](#license)

[Apache-2.0](https://github.com/buluma/ansible-role-demo/blob/master/LICENSE).

## [Author Information](#author-information)

[buluma](https://buluma.github.io/)

### Get Help
- Report issues: https://github.com/buluma/ansible-role-demo/issues/new
- See docs: https://docs.ansible.com/collection/gallery/ansible-role-demo
