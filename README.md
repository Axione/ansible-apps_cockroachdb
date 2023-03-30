# ansible-apps_cockroachdb

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_cockroachdb-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_cockroachdb)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_cockroachdb.svg)](https://github.com/lotusnoir/ansible-apps_cockroachdb/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_cockroachdb?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_cockroachdb)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_cockroachdb)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_cockroachdb)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure cockroachdb
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_cockroachdb
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_cockroachdb


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
