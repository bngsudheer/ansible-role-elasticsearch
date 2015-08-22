Elasticsearch
=========
Installs Elasticsearch on CentOS 7.

Installation Instructions:
------------

To install this role:
ansible-galaxy install bngsudheer.elasticsearch

Requirements
------------

Java Runtime Envorinment. If you want to install Java take a look at the role ansiblebit.oracle-java.

Role Variables
--------------

No variable declaration required.

Dependencies
------------

No dependencies.

Example Playbook
----------------

Example of how to use bngsudheer.elasticsearech:

    - hosts: servers
      roles:
         - { role: bngsudheer.elasticsearch  }

License
-------

BSD

Author Information
------------------
Role written by Sudheer Satyanaraya. http://www.techchorus.net
Twitter: http://www.twitter.com/bngsudheer

