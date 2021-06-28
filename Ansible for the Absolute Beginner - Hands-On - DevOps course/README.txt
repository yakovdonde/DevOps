Welocme to my "" Udemy course completion project.
"" playbook created an online store automatically.
The goal is to make all manual process automatically and not the store itself.

----- How to run the playbook? ------
the palybook executes commands as "sudo user", so you must to run the playbook with sudo user credentials.
EXAMPLE:
Te SUDO user credentials are:
username: bob
password: bob
So you should run this playbook as following:
ansible-playbook ydonde_playbook -i inventory.txt -u 'bob' -k --extra-vars "bob"