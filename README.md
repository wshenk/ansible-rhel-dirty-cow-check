
Sample way to run this ansible script

1st: Setup the inventory.yml file to hold the correct ip addresses

2nd: Run the script as shown below

```
export ANSIBLE_HOST_KEY_CHECKING=False
ansible-playbook -u <username> --key-file <ssh_key_file> -i inventory.yml check_hosts.yml
```
