# News Reporter

## 📋 Sobre o Projeto

- O projeto é uma infraestutura para suportar uma aplicação web.
- O objetivo é criar localmente uma infraestrutura em contêineres utilizando Docker e Kubernetes.

## Sobre a Aplicação:

- A aplicação é um Portal de Notícias. 
- O objetivo é permitir criar, visualizar e gerenciar artigos através de uma interface web.
- A aplicação foi construida utilizando Node.js.
 
### Funcionalidades Principais

- Listagem de notícias na página inicial
- Criação de novas notícias através de formulário
- Visualização detalhada de cada notícia
- API REST para inserção em massa de notícias
- Endpoints de health check para monitoramento
- Coleta de métricas para Prometheus

### Tecnologias Utilizadas

- **Backend**: Node.js com Express.js
- **Frontend**: EJS (Embedded JavaScript) como motor de templates
- **Banco de Dados**: PostgreSQL com Sequelize ORM

## 🔧 Configuração

### Pré-requisitos

- Node.js
- PostgreSQL
- Docker (opcional, para containerização)
- Kubernetes (opcional, para orquestração)


## Como utilizar o projeto:

### Executando o projeto:
```sh
# Executando o K8S
kubectl apply -f k8s/deployment.yaml

# Acessando o projeto
https://localhost:30000
```

### Comandos úteis:
```sh
# Exibindo o status do deploy
kubectl get deploy

# Exibindo o status do replicaset
kubectl get replicaset

# Exibindo o status dos Pods
kubectl get pod

# Exibindo todos os status
kubectl get all

```