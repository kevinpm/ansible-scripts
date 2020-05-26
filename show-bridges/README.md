# Show bridges
Ansible playbook used to check bridges in linux machines  
Command: ``` ansible-playbook bridges.yml --ask-pass -i vewlc-hosts ```  
Connectivity can be checked with the command ```ansible all -m ping -i vewlc-hosts --ask-pass```
