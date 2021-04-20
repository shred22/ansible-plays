vaultPass: passw0rd

# To Run the playbook, run thebelow command
ansible-playbook -i inventory.txt role-playbook.yaml --ask-valut-pass

# Or You can also use below command
ansible-playbook -i inventory.txt role-playbook.yaml -vault-password-file=./vaultpass.txt
