# DSE Workload Automation on vSphere

Automatically deploy DSE (**6.8**) clusters on vSphere using Terraform and Ansible. The automation may or may not work for other DSE versions.

# Prerequisites

The following dependencies are required to run this tool:
- Terraform
- Ansible
- sshpass

If above packages are not installed on your system, you can clone this repo and run the command to install: `bash ./env_prep.sh`. 

In addition, an **Ubuntu 20.04** ova template is required to configure the DSE cluster. Make sure the template is accessible via ssh with username and password. Other Ubuntu versions may or may not work.

## Instructions
Customize the deploy.cfg file in this repo and run the command `bash ./deploy.sh` to start the automation. 

**Please note the \*.sh files in this repo are based on bash, simply run `./*.sh` or `sh ./*.sh` won't work. Use `bash ./*.sh` instead.**
