[ ![Image](https://cloud.githubusercontent.com/assets/5514990/24834935/e0d1db04-1d1c-11e7-8ad0-53fd45ff13c3.png "Ansible") ](https://www.ansible.com/ "Ansible")

[![Build Status](https://travis-ci.org/ansyble/role-ulogd2.svg?branch=master)](https://travis-ci.org/ansyble/role-ulogd2)
[![Ansible Role](https://img.shields.io/ansible/role/xxx.svg)](https://galaxy.ansible.com/ansyble/ulogd2/)

[Ansible](http://www.ansible.com) role to deploy ulogd2.

### Install

```sh
ansible-galaxy install ansyble.ulogd2
```

### Defaults

```yml
ulogd2_loglevel: 3
ulogd2_json_file: /var/log/ulog/ulogd.json
ulogd2_json_device_name: elastic
```
