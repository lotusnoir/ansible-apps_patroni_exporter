# ansible-apps_patroni_exporter

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_patroni_exporter-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_patroni_exporter)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_patroni_exporter.svg)](https://github.com/lotusnoir/ansible-apps_patroni_exporter/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_patroni_exporter?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56096)](https://galaxy.ansible.com/lotusnoir/apps_patroni_exporter)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56096)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Deploy [patroni_exporter](https://github.com/momorientes/patroni_exporter) to expose patroni metrics to prometheus.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_patroni_exporter
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_patroni_exporter

## Grafana Dashboard

You can find a grafana dashboard [here](https://grafana.com/grafana/dashboards/13556)

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

