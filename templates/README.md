#Ansible and CloudFormation
Ansible plays to install beta version of the Juniper vSRX in AWS using CloudFormation.
After being deployed in AWS, ansible will wait for vSRX to come up and will put setup some basic configuration.
From this point Juniper.junos Ansible role used to configure the vSRX.
