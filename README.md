# My Ansible
## Best Practice of Ansible directory structure

```
playbooks
├── development
├── others.yml
├── production
├── roles
│   ├── common
│   │   ├── handlers
│   │   │   └── main.yml
│   │   ├── tasks
│   │   │   └── main.yml
│   │   └── templates
│   │       └── ntp.conf.j2
│   └── nginx
│       ├── handlers
│       │   └── main.yml
│       ├── tasks
│       │   └── main.yml
│       └── templates
│           └── default.j2
├── site.yml
├── staging
└── webservers.yml
```
