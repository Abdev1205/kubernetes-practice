### How to create service

- `kubectl create -f ./service-def.yaml `

### How to get Service

- `kubectl get svc`

### How to access that deployment

- `minikube service myapp-service --url`

```
http://127.0.0.1:61535
❗  Because you are using a Docker driver on windows, the terminal needs to be open to run it.

```

### How pods can internally access the server

- If we have complex system like We have Frontend , backend and database and they need to connected

- Everything is same just we have change the spec type of Cluster Ip and we can use that Ip to interact with each other
