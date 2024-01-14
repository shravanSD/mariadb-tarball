MariaDB Tarball
=========

This role install MariaDB server 10.6 using Binary Tarball from official MariaDB repositories.

Role Variables
--------------

Some defaults have been added to download mariadb server version 10.6 and to create the data dir in "/data/mysql"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - mariadb-tarball

License
-------

BSD
