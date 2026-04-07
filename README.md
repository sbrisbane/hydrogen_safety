# hydrogen_safety
Hydrogen Safety Code

## Installing ##

Secrets have been removed from this github repository.  You will need a copy of these files existing 
 - /home/applications/.hysaf/ansible_key
 - /home/applications/.hysafe/ansible_key.pub
 - /home/applications/.hysafe/ansible_vault_pass
 - /home/applications/.hysafe/secrets.yml 


## Dependencies ##

This module requires robertdebock.grub ansible module as a dependency (https://github.com/robertdebock/ansible-role-grub)
It uses the apache license v2.0.1

We supply a version of this for convenience, but be aware that this is third party software and of the appropriate license agreement

If you choose to upgrade this independently, replace it in ansible/roles/robertdebock.grub


