kwriteconfig
=========

This tool is a wrapper for kwriteconfig, to assist in configuring KDE desktop environment.

Requirements
------------

Ensure you have kwriteconfig5 installed.

Role Variables
--------------

The following vars will be needed. No code written yet.

  - display - default:0 - used to restart KDE if `restart_after` is set
  - restart_after - default:true - will restart KDE to reload new configuration
  - commands (paramaters of kwriteconfig)
    - name
    - file
    - group
    - key
    - type
    - value

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: benyanke.kwriteconfig, restart_after: false }

License
-------

GPLv3

Author Information
------------------

Created by Ben Yanke.
