### How to create replica

- `kubectl create -f <replica-set.yaml>`

### Get the Replica set

- `kubectl get replicaset`

### Delete the Replica

- `kubectl delete replicaset <replica-name>`

### How to scale or increase replica

- `kubectl scale -replicas=6 -f <replica-set.yaml>`
