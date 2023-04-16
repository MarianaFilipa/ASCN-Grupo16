# ASCN-Grupo16

## Objectives:

Project developed for the course "Cloud Computing Applications and Services" of a Software Engineering Masters. The goal of this project was to automate the process of installing, configuring, monitoring and evaluating the application **Ghost**. For this project, we used Ansible to configure and install the application on Google Kubernetes Engine (GKE) and monitored the performance using Google Cloud Platform.


## Components:

* *create-gke-cluster.yml* : Create the GKE Cluster.

* *destroy-gke-cluster.yml* : Delete the GKE Cluster.

* *deploy-ghost.yml*: Install, configure and execute Ghost's components in the GKE created.
   
* *undeploy-ghost.yml*: Undeploy the Ghost's components created previously.

    1. The data of the application is only deleted if the flag *-e delete data = true* is presented.

* *test-all.yml*: Allows to execute a series of automatic tests.


## Developed by:
- [Cláudia Silva](https://github.com/Claudia54)
- [Eduardo Magalhães](https://github.com/edumagalhaes10)
- [Laura Rodrigues](https://github.com/Laura-Rodrigues)
- [Mariana Rodrigues](https://github.com/MarianaFilipa)
- [Rui Alves](https://github.com/ruipedrolousada)

* **Project Grade**: 18
