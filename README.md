Role Name
========

Installs AWS command line tools on a server.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
-------------------------

Very simple installation of AWS CLI tools.

    - hosts: servers
      roles:
         - { role: craigmj.aws.cli }

License
-------

BSD

Author Information
------------------

Craig Mason-Jones (craig@lateral.co.za), Lateral Alternative. Github: http://github.com/craigmj/craigmj.aws.cli
