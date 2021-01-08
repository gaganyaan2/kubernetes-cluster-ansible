### Kubernetes cluster with ansible

1. Update the hosts information in hosts file

2. Run below ansible script to setup kubernetes cluster

`ansible-playbook -i hosts dependency.yml`

`ansible-playbook -i hosts master.yml`

`ansible-playbook -i hosts worker.yml`

### Upgrade kubernetes cluster

`ansible-playbook -i hosts upgrade-cluster.yml`