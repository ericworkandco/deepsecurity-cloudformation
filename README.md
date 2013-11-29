AWS CloudFormation template for Deep Security Manager 
=====================================================

- 2013/12/04 rev 1.1

Description
-----------

This template create below AWS components


Parameters
----------



Usage
-----


the DSM EC2 instance is based on CentOS 6 AMI, but bare-metal AMI is imcompatible with this template because of below points.

- not compatible with iptables default policy
- not compatible with SELinux
- to assume SSH Key deploy, install cloud-init

so, first create AMI by packer with `centos_cloud-init.json`


Author
------

- Ryuta Otaki otaki.ryuta@classmethod.jp 


License
-------

See at LICENSE.md

