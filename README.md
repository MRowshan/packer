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

## To create a packer image
Run the command `packer build -var-file=variables.json template.json`

## packer-script
Installs packer from hashicorp and all the relevant packages required to install it.

## template.json
Information required to set up an image with GCP

## variables.json
Variable values which are given to template.json when packer build is run
