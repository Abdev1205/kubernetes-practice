## Limit Range

### Why it is required

- It helps us to manage the resources efficiently
- It helps us to avoid the starvation of resource

### Stucture

- Everything is same as we have for other
- Kind : LimitRange

```
spec:
  limits:
  - default:
      cpu:500m
    defaultRequest
      cpu:500m
    max:
      cpu: "1"
    min:
      cpu: 100m
    type: container

```
