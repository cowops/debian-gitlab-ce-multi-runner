Debian-Gitlab-ce-multi-runner
=============================

GitLab runner for continuous integration service

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

- cowops.debian-gitlab-ce

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-gitlab-ce-multi-runner }

Tasks
-----

  - Install dependencies
  - Install [docker](https://www.docker.com/)
  - Install [gitlab-ce-multi-runner](https://about.gitlab.com/2016/08/05/continuous-integration-delivery-and-deployment-with-gitlab/)


License
-------

BSD
