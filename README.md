<img style="float:left" alight="left" height="128px" width="128px" src="https://github.com/iaroslavb/ansible-role-gitlab-runner-logo/raw/master/runner_logo.png">

Ansible Role: GitLab Runner (Docker)
=========

Ansible role for installing and configuring GitLab Runner

Requirements
------------

Environment variables should be exported on ansible controller machine before applying this role

```
GITLAB_RUNNER_TOKEN:  token used for registering new GitLab Runner on the server
GITLAB_SERVER_FQDN:   Gitlab Server domain name
GITLAB_SERVER_IP:     Gitlab Server ip
```

Role Variables
--------------

TODO

Dependencies
------------

TODO

Example Playbook
----------------

TODO

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Creater by Yaroslav Bannov
