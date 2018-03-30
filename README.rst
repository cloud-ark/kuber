======
Kuber
======

A deployer that hides complexities of Kubernetes and turns your Docker setup into a Kubernetes developer workspace.


**Application-centric abstractions**

Environment is a top level abstraction. 
Application is composed of one or more application container/s and is deployed in the environment. 


**Declarative application definition**

Easy way to define entire application stack. 

- env.yaml - definition of dependent resources within an environment

- app.yaml – definition of application container/s.


**Simplified deployment process**

Following two commands enable application deployment without having to learn complex Kubernetes constructs: 

- cld env create -f env.yaml

- cld app deploy -f app.yaml


Check https://github.com/cloud-ark/caastle for installation for GKE and usage examples.
