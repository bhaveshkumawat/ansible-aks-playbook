# ansible-aks-playbook
ansible playbook to create a managed aks cluster
<br>pre-requisite for this playbook:-<br>
Create an ansible vault encrypted file with the name secret.yaml that should contain variables named with and their values:-<br>
1. client_id
2. client_secret
3. ssh_key
<br>
or you can also can remove the vars_files: segment and directly declare the variable and cna use them (not preferred to have such values as plain text directly in the playbook)
