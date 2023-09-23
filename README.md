# ansible_website
Ansible Web Deployment Automation simplifies website deployments to remote servers using Ansible's capabilities.

In hosts.txt change/add servers.
In group_vars/defaults change/add settings for [defaults] inventory group. (for example private ssh key)

After making changes run: 
    ansible-playbook playbook3.yml 
