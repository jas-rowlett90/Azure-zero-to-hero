# Command to create ACR ImagePullSecret

```
kubectl create secret docker-registry acr-secret \
    --namespace default \
    --docker-server=jasazurecicd.azurecr.io \
    --docker-username=jasazurecicd \
    --docker-password=8GZrSoSc0qoFOnAOTmgLtTnNuDDWvC5MEbwAc8nWYV+ACRCjFEaF
```
