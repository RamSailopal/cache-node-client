Role Name
=========

This role automates the process of installing the neccesary Cache client Nodejs libraries to allow connection to a Cache database via Nodejs.

Requirements
------------

It is assumed that Cache is to be installed somewhere on the network to allow testing.

It is also assumed that that the Service integration gateway is also installed (see cache-node-server for details of installation)

Role Variables
--------------

hst - The address of the Intersystems Cache server

[ Default - localhost ]


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      role: cache-node-client
      hst: cacheserver 
      ...

Further Information
-------------------

The npm package referencing in the role:

https://www.npmjs.com/package/mg-dbx

License
-------

BSD

Author Information
------------------

Raman Sailopal
