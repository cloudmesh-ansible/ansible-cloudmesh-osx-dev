Cloudmesh OSX DEV
=================

Collection of ansible roles to make OSX more usable for development

Instalation of a particular topic::

  ./bin/cm install analytics
  ./bin/cm install editor
  ./bin/cm install graphics
  ./bin/cm install systems

or with original ansible script::
  
  ansible-playbook -i inventory.txt  analytics.yml --ask-become-pass


Refernces
=========

#. https://github.com/mpereira/macbook-playbook

