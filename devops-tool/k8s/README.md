# Creare Cluster
## Method1
> eksctl create cluster -f cluster.yaml
> eksctl create cluster --config-file=<path>
## Method2
> eksctl create cluster --name eksctl-demo --region=us-east-2 [--profile <profile-name>]
# View cluster

> eksctl get cluster [--name=<name>][--region=<region>]