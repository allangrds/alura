# Kubernetes: Introdução a orquestração de containers
## Comandos
##### minikube start
O comando pode ser usado para iniciar seu cluster. Esse comando cria e configura uma máquina virtual que executa um cluster Kubernetes de nó único. Esse comando também configura sua instalação do kubectl para se comunicar com esse cluster.

---

##### kubectl create -f application.yml
Peço para criar um objeto pod que está no arquivo application.yml.

---

##### kubectl get pods
Mostra os pods em execução.

---

##### kubectl delete pods application
Remove o pod "application".

---

##### kubectl create -f deployment.yaml
Peço para criar um objeto deployment que está no arquivo deployment.yml.


---

##### kubectl get deployments
Mostra os deployments em execução.

---

##### kubectl describe pods
Mostra informações dos pods ativos

---

##### kubectl describe pods | grep IP
Mostra IP dos pods ativos

---

##### minikube dashboard
Start servidor local para gerenciar e ver informações do cluster

---

##### text
text

---

## Outros
Link do curso [aqui](wee)