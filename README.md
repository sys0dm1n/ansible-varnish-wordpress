Role
========

This playbook is tested on Ubuntu server (Precise, Lucid and Trusty). It installs Varnish for Wordpress sites


Requirements
------------

You should have your Wordpress site running and your webserver is listening on port 80.
The operating system on which Varnish will be installed should be installed.

Variables
--------------
* Apache_backend_IP: The IP of your webserver hosting Wordpress site

Example
-------------------------
In the varnish-install.yml file, replace "hostname.com" with the hostname declared in your hostfile and replace "username" by the user that is allowed to remote connect via SSH with sudo privileges.


$ ansible-playbook -kK varnish-install.yml


It will prompt you for the user's password and for the sudo password as well

License
-------

GNU GPL v2.0

Author Information
------------------

sys0dm1n

http://terraltech.com/

http://chemaly.ca/
