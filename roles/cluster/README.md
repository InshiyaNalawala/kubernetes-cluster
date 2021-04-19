Role Name
=========

Use this role to launch EC2 instances on AWS. 


Requirements
------------

1. Create a valid Ec2 account
2. Generate IAM user credentials with Programmatic Acces. 

Role Variables
--------------

The role uses variables to define what type of instance, how many and in which region should the instance be launched. Make sure you provide valid credentials in the vars file before running the playbook. 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - role: "cluster"

