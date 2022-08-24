Role Name
=========

Download and Install Wordpress

Requirements
------------

Requried web_server and mariadb_server roles which are in the same repogitory.

Role Variables
--------------
Variables are located in group_vars/server_group_1 file. Please change the database name, database user and password accordingly.

Dependencies
------------
Requried web_server and mariadb_server roles which are in the same repogitory.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - web_server
         - mariadb_server
         - wordpress

License
-------

BSD

Author Information
------------------

Md. Imran Ali
System Administrator
