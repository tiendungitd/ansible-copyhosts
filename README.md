--Ansible copy hosts file to another

1. Modify the hosts file and update another ansible client

2. Modify your hosts at /etc/hosts

3. Push hosts updates to another by command
   #ansible-playbook -i hosts copy-host.yml --private-key='/path-to-ssh-key' -v