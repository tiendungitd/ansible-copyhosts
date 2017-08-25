--Ansible copy hosts file to another
ansible-playbook -i hosts copy-host.yml --private-key='/path-to-ssh-key' -v