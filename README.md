# ansible-haproxy
Ansible role for HAProxy 1.5 (CentOS7)

# Features
* Multiple Frontend and Backend support
* Get SSL-Certs from Ansible Vault
* Add predefined headers (HAProxy information, inly viewable from IPs marked as internal)
* Add Custom Headers
* Mark backends as internal (via ACL)
* Check config, only start/restart if config check succeeded
* Define stats uri
* Add rsyslogd config to log to /var/log/haproxy.log

# Missing features
* Logging configuration
* aso

# Manual
Check defaults/main.yml, there are already defaults and examples.


# Author Information

This role was created in 2016 by sBlatt, based on [ansible-haproxy](https://galaxy.ansible.com/geerlingguy/haproxy/) by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
