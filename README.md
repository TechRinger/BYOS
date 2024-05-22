# BYOS

## How to run playbook

1. Update devices in invenotry.yml
1. Run command from CLI:

``` bash
ansible-playbook -i ./inventory/inventory.yml ./playbooks/main_playbook.yml --extra-vars "ubuntu_user=[your_ubuntu_username] ubuntu_password=[your_ubuntu_password] windows_user=[your_windows_username] windows_password=[your_windows_password]"
```
