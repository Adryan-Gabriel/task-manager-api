# Task Manager API — Spring Boot

Uma API RESTful simples desenvolvida em Java com Spring Boot para o gerenciamento de tarefas (CRUD). O objetivo principal deste projeto é demonstrar o entendimento prático do protocolo HTTP (verbos GET, POST, DELETE), manipulação de dados no formato JSON e o ciclo de vida de aplicações em memória.

---

## Tecnologias Utilizadas

* Java 17+
* Spring Boot
* Jackson (ObjectMapper) — para serialização e formatação de JSON
* cURL — para testes e validação de rotas no terminal Windows/PowerShell
* VS Code — IDE de desenvolvimento

---

## Funcionalidades e Endpoints

A API opera com armazenamento em memória (ArrayList), tornando as requisições rápidas para testes e validação das rotas RESTful.

| Método | Endpoint | Descrição | Corpo da Requisição |
| :--- | :--- | :--- | :--- |
| GET | /tasks | Lista todas as tarefas cadastradas | N/A |
| POST | /tasks | Adiciona uma nova tarefa à lista | Texto simples (text/plain) |
| DELETE | /tasks | Limpa toda a lista de tarefas | Texto simples (text/plain) |

---

## Como Testar a API Localmente

### Pré-requisitos
* Java JDK instalado
* Maven (ou Maven Wrapper do próprio projeto)

### 1. Clonar e Executar o Projeto

```bash
# Clone o repositório
git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)

# Entre na pasta do projeto
cd NOME-DO-REPOSITORIO

# Execute a aplicação com Maven
./mvnw spring-boot:run
