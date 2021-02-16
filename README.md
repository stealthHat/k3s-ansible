# Ansible roles for my raspberry cluster

## Roles
 - pi-config: Makes the basic configuration of the system
 - k3s-config: Makes the changes needed to run k3s on raspberrypi OS
 - k3s : Install de k3s service and configure the control plane
 - k3s-node : Adds nodes to the control plane 

To run add the master and nodes ips to a inventory file and run it with ansible :)

# [DEPRECATED]
  im using [this](https://github.com/stealthHat/k8s-ansible) repo for my raspberry cluster.
