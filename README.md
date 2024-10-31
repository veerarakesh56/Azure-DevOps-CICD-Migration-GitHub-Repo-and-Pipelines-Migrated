# Ultimate-Azure-CICD

# Create-acr-secret-command:

# Command to create ACR ImagePullSecret

```
kubectl create secret docker-registry <secret-name> \
    --namespace <namespace> \
    --docker-server=<container-registry-name>.azurecr.io \
    --docker-username=<service-principal-ID> \
    --docker-password=<service-principal-password>
```
