# ansible-roles-app-install
Ansible Roles for Provisioning ECs instance and configuring simple python app with mySQL and Flask.

# Preconfigure
Add the private key of currrnt running instance in the server1.pem file.

# Run
> ansible-playbook install-app.yml -e "aws_access_key=< value > aws_secret_key=< value >" -vv
### NOTE : Use the aws_access_key and aws_secret_key of current running instance at relevant values in the above command.
