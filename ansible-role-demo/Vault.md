vaultPass: passw0rd

# To Run the playbook, run thebelow command
ansible-playbook -i inventory.txt role-playbook.yaml --ask-valut-pass

# Or You can also use below command
ansible-playbook -i inventory.txt role-playbook.yaml -vault-password-file=./vaultpass.txt

# To View Encrypted inventory, use
ansible-vault view inventory.txt

# To Create encrypted inventory, use
ansible-vault create inventory.txt

