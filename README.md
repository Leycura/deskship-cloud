# Deskship-Cloud - Cloud Configuration

## Overview
This Repository is created to deploy the web application "Deskship" as a cloud deployment.

## Used Versions

- Minikube v1.25.1 on Ubuntu 20.04
- Kubernetes v1.23.3 (client)
- Kubernetes v1.23.1 (Minikube) 

## Notes:
 
To get Minikube [access to local docker images](https://kubernetes.io/de/docs/setup/minikube/):

```
eval $(minikube docker-env). 
```

Expose services of type [LoadBalancer in Minikube](https://minikube.sigs.k8s.io/docs/handbook/accessing/#using-minikube-tunnel):

```
minikube tunnel
```



## ToDo's

### Research

- More about PVC! 
- Which Cloud?
- Nginx-Ingress or else? (depending on Cloud)

### Code

- Test Backend with Postgres
- Create Postgres with initial script (test data)

---  ***more coming soon*** ---
