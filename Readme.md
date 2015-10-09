# Nomad Cluster
This project provides a way to quickly spin up a test nomad cluster with three servers and one client, each agent on their own VMs.

## Commands
```shell
$ vagrant up
```

## Caveats
This project is very opinionated on some on some of the setup, such as data and config directories and private network IPs.
Feel free to change those to suit your particular needs.

As of Nomad 0.1.2 there is no Consul integration, and therefore vagrant-hostmanager is used to manage discovery of nodes

## Prerequisites:
Vagrant 1.7.4+
vagrant-hostmanager