# ansible-mysql
## Commnads Used

To install the mysql in local system 
commands used 
```
ansible-playbook main.yml
```
To encrypt the sesitive variable files  with password
```
ansible-vault encrypt group_vars/all
```

Play with encrypt  
```
ansible-playbook --ask-vault-pass main.yml
```

Decrypt the password on variable file
```
ansible-vault decrypt group_vars/all
```
