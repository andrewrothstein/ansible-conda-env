[![Build Status](https://travis-ci.org/andrewrothstein/ansible-conda-env.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-conda-env)
andrewrothstein.conda-env
=========

A role to create a [Conda](http://conda.pydata.org/docs/index.html) environment.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: andrewrothstein.conda-env
	  conda_env_name: ansible
	  conda_env_python: 2.7
	  conda_env_environment: environment.yml
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
