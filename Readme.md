The playbook installs an ansible-awx example installation on an Ubuntu server.

Prerequsities:
* Ansible 2.16+

How to start:
1. Checkout this repo.
2. Load requrements:
```
ansible-galaxy install -r requirements.yml
```
3. Edit the hosts file, add a host you want to provision.
4. Change variables 'users' and 'awx\_password' in site.yml.
5. Run ansible-playbook site.yml (add -K if you need add a sudo password).


