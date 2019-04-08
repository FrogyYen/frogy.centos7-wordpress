frogy.centos7-nginx
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

none

Role Variables
--------------
```yaml
hostname: mywordpress
modify_hostname: true
wordpress_version: 4.4.2
wordpress_parent_path: /usr/share/
wordpress_path:        "{{ wordpress_parent_path }}/wordpress"
wordpress_owner: root
wordpress_group: root
wordpress_db_name: wordpress
wordpress_db_user: wordpressuser
wordpress_db_password: wordpresspassword
```
Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
```
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
