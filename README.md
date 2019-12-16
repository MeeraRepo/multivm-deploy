Role Name
=========

Multiple-VM deployment.

Requirements
------------

This role should have the Azure Modules to be installed on Ansible Controller Machine, and their should be a connectivity between Ansible MasterVM and your Azure Subscription. 

Azure CLI Should be installed.

Role Variables
--------------

Role Variables like Resource Group Name, VNET Name, Subnet Name, Storage Account Name, Virtual Machine Names, Username and Password.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      connection: local
      roles:
         - { role: multivm-role }

License
-------
BSD
