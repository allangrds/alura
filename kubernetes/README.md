# Kubernetes: Introdução a orquestração de containers
## Comandos
##### minikube start
O comando pode ser usado para iniciar seu cluster. Esse comando cria e configura uma máquina virtual que executa um cluster Kubernetes de nó único. Esse comando também configura sua instalação do kubectl para se comunicar com esse cluster.

---

##### kubectl create -f application.yaml
Peço para criar um objeto pod que está no arquivo application.yaml.

---

##### kubectl get pods
Mostra os pods em execução.

---

##### kubectl delete pods application
Remove o pod "application".

---

##### kubectl create -f deployment.yaml
Peço para criar um objeto deployment que está no arquivo deployment.yaml.


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

##### kubectl create -f application-service.yaml
Peço para criar um objeto service que está no arquivo application-service.yaml.

---

##### kubectl get services
Mostra os services ativos

---

##### minikube service application-service --url
Retorna a url de acesso do service

---

##### kubectl create -f statefulset.yaml
Peço para criar um objeto statefulset que está no arquivo statefulset.yaml.

---

##### kubectl create -f database-service.yaml
Peço para criar um objeto service que está no arquivo database-service.yaml.

---

##### kubectl create -f permissions.yaml
Peço para criar um objeto contendo permissões ao pod.

---

##### kubectl exec -it database-statefulset-0 sh
Executa o shell de um determinado objeto

## Outros
Link do curso [aqui](wee)