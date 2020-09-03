# Kubernetes

This repo was originally tested against a managed Kubernetes cluster hosted by Digital Ocean.

Many of the components have defaults that assume a working default storage class and the ability to provision layer 4 load balancers.

# CA Prep Notes

*launched RMS using DO Terraform QS:
** Setup
*** rancher_node_ip = 68.183.22.134
*** rancher_server_url = https://rancher.68.183.22.134.xip.io
*** workload_node_ip = 157.230.53.27
