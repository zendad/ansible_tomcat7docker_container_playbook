ansible-role-tomcat7-docker-container
=========

An Ansible role to install Docker & tomcat7 docker container in Debian or Ubuntu.

Requirements
------------

64bit Debian / Ubuntu

installation
------------

    ansible-playbook playbook/site.yml 

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dereck.docker }
		 - { role: dereck.tomcat7}

