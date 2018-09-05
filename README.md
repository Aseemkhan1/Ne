# network
This is Ansible code to automate Cisco IOS router configuration backup. The "routers" is the group name in ansible file which
needs to match with host group in inventory file. the host group has IPs of all routers which needs to backup, This code will
create a seperate configuration file for each router with hostname or IP accordingly and copy to destination folder.
