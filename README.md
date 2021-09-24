# Development Enviroment set up

This project is about to set up development enviroment with ansible on Ubuntu-based linux.
In addition, to solve the wifi not not detected problem for wireless device `Realtek 8852`(see in the overview).

## Overview
* The `main.yml` is the main file, includes the used playbooks.
* The `tasks` folder containes all playbook files:
  - `realtekWIFIFix.yml` is for the wifi problem fix. If you do not have Realtek 8852/8952 then this fix is not needed and is useless. 

## Requirements
- Ansible


## Steps to run
1. **Clone the project**
	```bash
	git clone https://github.com/karesz123/DevelopmentSetUp.git
	cd DevelopmentSetUp
	```
2. **Run the main playbook**
	```bash
	ansible-playbook main.yml
	```
