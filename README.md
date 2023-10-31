# distributed-task-scheduler
distributed task scheduler implemented with Ansible

# Setup

- First create two files ```inventory``` and ```ansible.cfg``` and the add the following contents:
```
**inventory**
[workstations]
10.20.24.53
```
```
*ansible.cfg*
[defaults]
inventory = *inventory-file-name*
private_key_file = *path-to-your-private-ssh-key*
remote_user = *name-of-remote-user(optional)*
```
