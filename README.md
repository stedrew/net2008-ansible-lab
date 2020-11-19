# ansible-lab

Examples for Ansible Lab

## Requirements

* [Azure account](https://azure.microsoft.com/en-us/)
* [Ansible](http://docs.ansible.com/ansible/intro_installation.html)

## HowTo

* Install Ansible on your computer
* Clone this repo:

```bash
git clone https://github.com/zhuheec/ansible-lab.git
cd ansible-lab
```

## Examples

* ad-hoc commands

```bash
ansible -m ping all
ansible -m shell -a "whoami" localhost
```

* playbook commands

```bash
ansible-playbook -i inventory playbooks/01-simple.yml

```
