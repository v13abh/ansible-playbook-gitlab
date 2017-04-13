# Gitlab Installation using Ansible

##  Notes

This Ansible Playbook will install Gitlab  using an Ansible Role

## Requirements

* Requires [Ansible](http://docs.ansible.com/ansible/intro_installation.html)

## Installation

1. Clone this repo to a local folder.

2. Copy `my-vars.default.yml` to `my-vars.yml` and insert your particulars.

3. Execute the following command:

	"ansible-galaxy install -r requirement.yml --force"

4. Execute the following command: `

	"ansible-playbook gitlab.yml (Add -vvv for verbose installation.)"

5. Point your browser to the URL configured in my-vars.yml. You will be prompted to change the password for the Root account.

