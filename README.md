# Openstack-Pretty-Ports

Like other openstack commands port list command has a quite a few options for a user to narrow down the output to the desired information. However the info in tabular form sometimes overlap other columns and user need to stretch the console to max or to the width where all columns cant fit-in. 

usage: openstack port list [-h] [-f {csv,json,table,value,yaml}] [-c COLUMN]

I couldn't figure out how I can keep only desired columns simultaneiously. The -c option allow the user to display one column at a time. Either this option can't display the desired columns simultaneously or my ignorance on this inspired me to write a playbook in ansible

With reduced number of columns the user is asked for the keyword to choose the group and the playbook displays the ports for that category.

For example the user input 'vfab' would show virtual fabric ports. Here is the pretty print snippet, though looks ugly when info is not shown

![vfab](https://user-images.githubusercontent.com/47313728/102305703-87320f00-3f15-11eb-88be-3282f3290515.png)
