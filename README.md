# ASCN-Grupo16

## Componentes:

* *create-gke-cluster.yml* : Cria o cluster Kubernetes

* *destroy-gke-cluster.yml* : Elimina o cluster

* *deploy-ghost.yml* : Instala, configura e executar os componentes do Ghost no cluster criado antes.

    1) Instalação nova, ou instalação com dados
    2) Instalação com os dados indicados

* *undeploy-ghost.yml* : terminar a execução.\
    1) só com flag *-e delete data = true* se apaga os dados

* *test-all.yml* : Efetua um conjunto de testes automáticos