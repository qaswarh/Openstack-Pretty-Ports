# Openstack-Pretty-Ports
Openstack port list using Ansible
Like other openstack commands port list command has a quite a few options for a user to narrow down the output to the desired information. However the info in tabular form sometimes overlap other columns and user need to stretch the console to max or to the width where all columns cant fit-in. I couldn't figure out how I can keep only desired columns simultaneiously. The -c option allow you to display one column at a time. Either this option to display only desired columns simultaneously or my ignorance on this inspired me to write a playbook in ansible

This playbook not only reduced the columns but give the user keywords in the newtworks to choose the network from and displays the ports for that network.

