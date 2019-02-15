Infra Cluster Docker  ![](https://secure.travis-ci.org/wangwenpei/infra-cluster-docker.png?branch=master)
============================================================================================

Install a newer Docker-CE for CentOS.

Install
-------

```
ansible-galaxy install wangwenpei.infra-cluster-docker
```

Role Variables
--------------

see [here](./defaults/main.yml)


Example Playbook
----------------

For target machine

```
    - hosts: servers
      roles:
        - wangwenpei.infra-cluster-docker
```


License
-------

GPLv3

Author Information
------------------

Author: wangwenpei
