vagrant-server-playbook
=======================

Ansible playbook to install [vagrant](http://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org) on ubuntu/debian server server.

##Requirements##

- ansible 1.4.4

##Usage##

Configure ```hosts``` file with your server. Then execute:

```
ansible-playbook -i hosts site.yml
```

After that you will need to import some vagrant boxes and you ready to go.