# Deskship-Cloud - Cloud Configuration

## Overview
This Repository is created to deploy the web application "Deskship" as a cloud deployment.

## Used Versions

- Google Cloud SDK 375.0.0
- Kubernetes v1.23.4 (client)
- Kubernetes v1.23.4 (server) 
- CNI (Calico)

- Minikube v1.25.1 on Ubuntu 20.04 (testing local)

## Summary State Cloud

- Which Cloud? 
  - Google Compute Engine

- VM-Instances 
  - VM-Instance 1: controller (n1-standard-1)
  - VM Instance 2: worker-0 (n1-standard-1)

- DB
  - Postgres deployed as stateful set

- Frontend/Backend
  - Deployed in namespace deskship

## Notes:

### ToDo's

- Networking (Nginx Ingress Controller as Service)
- Connect with reserved domain


---  ***more coming soon*** ---

