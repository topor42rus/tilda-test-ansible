1. Add to hosts or inventory
# cat /etc/ansible/hosts
[test]
test-host ansible_ssh_host=****** ansible_port=***** ansible_ssh_pass=******

2. Run playbook
# ansible-playbook playbook.yaml
OR
# ansible-playbook -i inventory_file playbook.yaml
