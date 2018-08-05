# Kubernetes Installation

This repository will run Ansible playbook to install Kubernetes.
Currently, there are 3 playbooks:

* dependencies.yml - will configure the OS & install required packages: Docker, kubelet, kubeadm, kubectl
* master.yml - this playbook will create a cluster of 3 master nodes
* worker.yml - this playbook will join worker nodes into the cluster

This installation installs the default network plugin which is Calico
