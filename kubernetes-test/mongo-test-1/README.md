# mongo-express example
## functional on minikube
### tree
$ tree ../
../
├── mongo-test-1
│   ├── README.md
│   ├── mongo-configmap.yaml
│   ├── mongo-deployment.yaml
│   ├── mongo-express-deployment.yaml
│   ├── mongo-express-service.yaml
│   ├── mongo-secrets.yaml
│   ├── mongo-service.yaml
│   ├── st
│   ├── stat
│   └── status
│       └── mongo-express-deployment-result.yaml
└── test-1
    ├── README.md
    ├── nginx_deployment.yaml
    ├── nginx_service.yaml
    └── status
        └── nginx-deployment-result.yaml

4 directories, 14 files
#### expected minikube output
minikube service list
|-------------|----------------------------|--------------|---------------------------|
|  NAMESPACE  |            NAME            | TARGET PORT  |            URL            |
|-------------|----------------------------|--------------|---------------------------|
| default     | kubernetes                 | No node port |
| default     | mongo-express-test-service |         8081 | http://192.168.64.4:30101 |
| default     | mongodb-test-service       | No node port |
| kube-system | kube-dns                   | No node port |
|-------------|----------------------------|--------------|---------------------------|

