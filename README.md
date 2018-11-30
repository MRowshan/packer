# packer
Creates a CentOS7 image with relevant packages and git repos installed  
### Packages:  
- git
- wget
- unzip
- docker
- ansible
### Repositories:
- vim (config)
- ranger
- additional_tasks-QA (includes docker and git set up scripts)

## packer-script
Installs packer from hashicorp and all the relevant packages required to install it.
