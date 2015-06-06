correcthorse.app
=========

A generic role for installing applications from tar files or source code (eventually.) This role is currently very experimental and incomplete.

Role Variables
--------------

| Variable			| Default				| Notes				|
| :---				| :---					| :---				|
| app_name			| app					| 				|
| app_user			| app					|				|
| app_group			| undefined				|				|
| app_group_id			| undefined				|				|
| app_user			| undefined				|				|
| app_user_id			| undefined				|				|
| app_home			| undefined				|				|
| app_base_name			| undefined				|				|
| app_archive			| undefined				|				|
| app_extracted_name		| undefined				|				|
| app_download_url		| undefined				|				|
| app_shared_links		| undefined				|				|

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: correcthorse.app }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
