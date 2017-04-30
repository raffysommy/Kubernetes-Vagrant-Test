## Kubernetes-Vagrant-Test
# Just cd in directory and:


For Flannel:


vagrant up


For Calico:


vagrant up 


then login into the master:


kubectl apply -f calico.yaml 


and after 1 minutes 


kubectl apply -f skydns.yaml


