[![Build Status](https://travis-ci.org/wtanaka/ansible-role-dot-forward.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-dot-forward)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-dot-forward.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-dot-forward)

wtanaka.dot-forward
===================

Ansible role to create a .forward file in root's homedirectory to
forward local root mail to a different email address

Example Playbook
----------------

    - hosts: all
      roles:
         - role: wtanaka.dot-forward
           dot_forward_email: example@example.com

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
