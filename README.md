# Ultimate-Azure-DevOps-CICD (Complete Migration from GitHub to Azure Pipelines along with the Source Code)

## Original GitHub Repo used: "dockersamples/example-voting-app"
https://github.com/dockersamples/example-voting-app

"This project is based on the excellent work of the original GitHub repository 'dockersamples/example-voting-app'. All credit for the original design and implementation goes to the creators of the original repository. Thank you for creating such a great application!"

## Create-acr-secret-command:

### Command to create ACR ImagePullSecret

```
kubectl create secret docker-registry <secret-name> \
    --namespace <namespace> \
    --docker-server=<container-registry-name>.azurecr.io \
    --docker-username=<service-principal-ID> \
    --docker-password=<service-principal-password>
```
