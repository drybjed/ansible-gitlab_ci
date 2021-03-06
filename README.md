## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) gitlab_ci

[![Travis CI](http://img.shields.io/travis/debops/ansible-gitlab_ci.svg?style=flat)](http://travis-ci.org/debops/ansible-gitlab_ci) [![test-suite](http://img.shields.io/badge/test--suite-ansible--gitlab__ci-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-gitlab_ci/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.gitlab__ci-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1567)

[GitLab CI](https://about.gitlab.com/gitlab-ci/) is a continuous
integration service based around [GitLab](https://about.gitlab.com/). It
uses a GitLab instance for authentication and access to git repositories
(can be managed using `debops.gitlab` role) and
[GitLab CI Runner](https://github.com/gitlabhq/gitlab-ci-runner/) service
to run the tests (can be installed using `debops.gitlab_ci_runner` role).

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.gitlab_ci

### Documentation

More information about `debops.gitlab_ci` can be found in the
[official debops.gitlab_ci documentation](http://docs.debops.org/en/latest/ansible/roles/debops.gitlab_ci.html).


### Role dependencies

- `debops.etc_services`
- `debops.redis`
- `debops.nginx`
- `debops.mysql`
- `debops.ruby`
- `debops.secret`
- `debops.postgresql`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`gitlab_ci` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
