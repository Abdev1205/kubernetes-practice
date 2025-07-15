### Creating deployment

Same as Replica just here we have to change the kind

- `kubectl create -f <filename>`

### To Get Every detail

- `kubectl get all`

### To get rollout status

- `kubectl rollout status deployment/deployment-nam`

### To get rollout history

- `kubectl rollout history deployment/deployment-nam`

### TO rollback the Deployment

- `kubectl rollout undo deployment/<deployment-name>`
