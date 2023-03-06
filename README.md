# Absible Role: ntp
This role does configure chrony on RHEL and Ubuntu LTS Systems.


## Requirements
Please look into `meta\main.yml`

## Install Role from Git
```
git clone git@github.com:joe-speedboat/ansible.mtp.git /etc/ansible/roles/joe-speedboat.ntp
cd /etc/ansible/roles/joe-speedboat.ntp
rm -rf .git
``` 


## Install Role from Galaxy
```
ansible-galaxy install joe-speedboat.ntp
``` 



## Role Variables
Variables are speaking or documented in defaults/main.yml   
One variable is mandatory: vdoPhyDev 


## Dependencies
none


## Example Playbook
Are located in `test` folder of the role


## License
GPLv3


# Author Information
* Chris Ruettimann<chris@bitbull.ch>
* https://www.bitbull.ch 
