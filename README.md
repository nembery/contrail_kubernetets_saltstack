# Contrail + Kubernetes + Saltstack

Ansible playbok to standup an opencontrail + Kubernetes + Saltstack infra very quickly. Great for testing and to use as a base for building solutions.

Only possible because of the awesome work being done by the opencontrail team to containerize the controller pieces. 

## Why?

Everyone should be using this architecture :-)

## Acks

Lots of ideas borrowed from:

* https://github.com/dcj/ansible-kubeadm-cluster 
* https://github.com/kubernetes/kubernetes
* https://github.com/Juniper/contrail-docker

## Version

0.01 - 10-17-17 initial project creation

# FIXES required
add nfs-common package to kubernetes role
