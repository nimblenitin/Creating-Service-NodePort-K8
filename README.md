# Creating-Service-NodePort-K8
A NodePort is can be created to connect the Kubernetes cluster from outside the Node.

Simple example to create NodePort service with YAML-

Steps followed:

*As Root*
```
1. Create the Nginx deploy YAML file

2. Create the NodePort Service YAML file

3. Checout the service created.
$ kubectl describe service

4. Try accessing the Nginx server with the service
$ curl 10.108.171.109:9000 |grep title

*As Root*
```
