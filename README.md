# DevOpsThailand2018_Storage_K8S
Assumption:
	1. Kubernetes Farm was configured and setup
        2. Raw disk need to provide on worker node

Video for Setup:
Setup Part1: https://youtu.be/JQus1aheSM4

Video for Demo:
https://youtu.be/i4k-84MMQ-Y

Setup GlusterFS:
	Following "instruction_setup.txt" for operate. This base on https://github.com/gluster/gluster-kubernetes

Demo Wordpress:
	1. Create Etcd cluster: etcd-cluster.yaml
	2. Create Galara Mariadb: galeramariadb.yaml
        3. Create Wordpress with 10 Replicas: wordpress.yaml       
