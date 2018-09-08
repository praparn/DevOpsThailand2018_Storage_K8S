# DevOpsBKK2018_Storage_K8S
Assumption:
	1. Kubernetes Farm was configured and setup
        2. Raw disk need to provide on worker node

Video for Setup:
https://youtu.be/ulwyFgcmFsA

Video for Demo:
https://youtu.be/KcAN9PIQUlA

Setup GlusterFS:
	Following "instruction_setup.txt" for operate. This base on https://github.com/gluster/gluster-kubernetes

Demo Wordpress:

1. Create Etcd cluster: etcd-cluster.yaml

2. Create Galara Mariadb: galeramariadb.yaml

3. Create Wordpress with 10 Replicas: wordpress.yaml       
