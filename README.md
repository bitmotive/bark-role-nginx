BARK: NGINX
=========

Install and configure an NGINX installation.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**NGINX_REQUIRED_PORTS**:

A comma separated list of ports NGINX should server content on.


Dependencies
------------

Currently dependent on Debian/Ubuntu due to reliance on `apt` and `ufw`. 

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
