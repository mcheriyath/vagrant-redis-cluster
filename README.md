# vagrant-redis-cluster
Setup Redis Cluster using Vagrant and Ansible

This ansible play is based on [DavidWittman/ansible-redis](https://github.com/DavidWittman/ansible-redis) that installs redis.

#### How to run
``` yml
ansible-playbook -i hosts -vvvv --private-key=/Users/mcheriyath/.vagrant.d/insecure_private_key ansible-redis.yml

```
