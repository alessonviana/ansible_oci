# ansible on OCI

- The objective of this project is to create a lab using ansible to manage machines in Oracle Cloud (OCI).

- You can manage the machine accessing the portal https://www.oracle.com/cloud/sign-in.html

- For to run the playbook, use this command: $ ansible-playbook --vault-id <vault_password_file> -i hosts/<inventory_file> main.yml
- If you prefer, you can activate verbose mode, you can put -vvv at the end of the code.

[Exemeple] $ ansible-playbook --vault-id .ansible.vault -i hosts/oracle main.yml -vvv
