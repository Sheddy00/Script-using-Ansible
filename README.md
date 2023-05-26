# Script-using-Ansible
## Steps using Ansible
Here are the steps to follow for that :

# Step I : Installing Ansible
Be sure to install Ansible on the machine from which you want to automate configuration tasks.
For that you will have to use the commands for the installation according to your operating system
example on debian 11:
Run this command on the terminal `sudo apt install ansible` and don't forget to update first with this commandn `sudo apt update`.

# Step II : Inventory setup
Create an inventory file in which you specify the hosts on which you want to perform configuration tasks to include IP addresses and hostnames.

# Step III : Creation of playbooks
Playbooks are YAML files in which you define tasks to be performed on target hosts.

# Step IV : Definition of roles
Roles are an organized way to manage tasks in Ansible. You can group playbooks, variable files, and other related resources into roles.

# Step V : Configuring variables
Use variables to parameterize tasks and make your code more flexible. This makes it easy to tailor configuration tasks for different environments or target hosts.

# Step VI : Executing Playbooks
Once you have configured your playbooks, you can run Ansible to start automating configuration tasks. For this you can use the command 
`ansible-playbook -i `hostFile``
