# sovrin-environments
Methods and scripts for standing up Sovrin test environments for different use-cases.

The following are among the methods that can be used to set up a Sovrin Validator cluster for testing.  Others will be implemented in the future.

 - [CloudFormation, multiple VMs](#cloudformation) 
 - [Vagrant, multiple VMs](#vagrant)

## CloudFormation
Using the CloudFormation scripts, an admininstrator can create VPCs and VMs in AWS EC2. The scripts automate configuration tasks such as networking, installation of packages, and configuration of Sovrin Validator, Agent, and CLI client nodes.  The administrator must have an existing AWS account with adequate permissions, where he will paste in the CloudFormation script, modify it as necessary, and execute it.
## Vagrant
Using the Vagrant and bash scripts, an administrator can create VMs in his own PC (Linux, Mac, or Windows), provided that it has adequate storage, memory, and CPU cores.  The scripts automate installation and configuration of Sovrin software on the VMs, creating Sovrin Validator, Agent, and CLI client nodes.  Freely available VirtualBox and Vagrant software must be installed before executing these scripts.  The "[TestSovrinClusterSetup.md](vagrant/training/vb-multi-vm/TestSovrinClusterSetup.md)" file in the vagrant/training/vb-multi-vm/ directory documents the installation and use of the Vagrant scripts.

