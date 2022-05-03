# k8s
A working kubernetes deployment

### K8s manifest files 
* mongo-config.yaml
* mongo-secret.yaml
* mongo.yaml
* webapp.yaml

### Pre-requisits
#### on MAC
#### Install minikube
    brew install minikube
    minikube --version

### Quick Start
#### K8s commands

##### start Minikube and check status
    minikube start --driver docker 
    minikube status

##### get minikube node's ip address
    minikube ip

##### apply all yaml files within the application directory
    kubectl apply -f application/
    minikube service webapp-service

##### get basic info about k8s components
    kubectl get node
    kubectl get pod
    kubectl get svc
    kubectl get all

##### get extended info about components
    kubectl get pod -o wide
    kubectl get node -o wide
