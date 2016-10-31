ansible-centos
====

Ansible playbooks for CentOS

## Description

Make a configuration of servers by Ansible.

- provides
```
├── hosts
├── site.yml
└── roles
    ├── glassfish
    │   └── 4.1
    │       ├── files
    │       │   └── glassfish.service
    │       ├── tasks
    │       │   └── main.yml
    │       └── vars
    │           └── main.yml
    ├── java
    │   └── 8
    │       ├── tasks
    │       │   └── main.yml
    │       └── vars
    │           └── main.yml
    └── postgresql
        └── 9.5
            ├── tasks
            │   └── main.yml
            └── vars
                └── main.yml
```

## Requirement

- Ansible 2.0+

## Usage

1. Run ansible playbook.

```
$ ansible-playbook -i hosts site.yml
```

## Licence

[MIT](https://github.com/satoyuki8478/ansible-centos/blob/master/LICENSE)

## Author

[satoyuki8478](https://github.com/satoyuki8478)
