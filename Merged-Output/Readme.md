#Goals of this Ansible Playbook:

1. Send one-or-more CLI commands to one-or-more network devices (Routers, Switches, etc)
2. Save output from each device to a file in the Ansible Control Node
3. Prepend each file with the inventory hostname of each device and a blank line
4. Merge individual files into a single file
