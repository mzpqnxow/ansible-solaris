## Notes

This is NOT a secure/hardened build, it may in fact undermine the security of your system. Please only use in test/lab environments !!

## What you need to change

Change the values in defaults/main.yml and vars/main.yml to suit your needs

## How to use as a full Ansible environment

You will need to change ansible/etc/ansible.cfg, ansible/etc/hosts and shellrc for your specific environment. You will also need to change the key information. Once you do this, you can use the following command to build the Ansible environment:

```
$ make
$ source venv/bin/activate
$ source shellrc
$ ansible -mping all
```

## Issues / bug requests

Feel free to enter them but I'm not really supporting this for other users
