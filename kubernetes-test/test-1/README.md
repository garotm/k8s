# nginx
### testing using configs and minikube
#### output:
    $ minikube service nginx-test1
|-----------|-------------|-------------|---------------------------|
| NAMESPACE |    NAME     | TARGET PORT |            URL            |
|-----------|-------------|-------------|---------------------------|
| default   | nginx-test1 |          80 | http://192.168.64.4:30100 |
|-----------|-------------|-------------|---------------------------|
🎉  Opening service default/nginx-test1 in default browser...

### what this looks like
.
└── test-1
    ├── README.md
    ├── nginx_deployment.yaml
    ├── nginx_service.yaml
    └── status
        └── nginx-deployment-result.yaml

2 directories, 4 files
