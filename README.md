Ansible Role: Kubernetes Dashboard
=========

Deploy [Kubernetes Dashboard](https://github.com/kubernetes/dashboard)

Requirements
------------

- Kubernetes setuped

Role Variables
--------------

`k8s_dashboard_conf`: The kubernetes config file for dashboard. Default: https://raw.githubusercontent.com/kubernetes/dashboard/master/src/deploy/recommended/kubernetes-dashboard.yaml

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: master
  become: yes
  roles:
    - { role: djx339.k8s-dashboard }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
