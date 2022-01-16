# mongo-express example
## functional on minikube
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

