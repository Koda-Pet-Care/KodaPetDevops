# KodaPet DevOps

Projeto DevOps da plataforma KodaPet desenvolvido para automação de infraestrutura, integração contínua e containerização da aplicação.

---

## Tecnologias Utilizadas

- Docker
- Docker Compose
- PostgreSQL
- GitHub Actions
- Java 17
- Spring Boot
- Git/GitHub

---

## Estrutura do Projeto

O ambiente foi desenvolvido utilizando containers Docker para padronização e facilidade de deploy.

A automação CI/CD foi implementada utilizando GitHub Actions.

---

## Serviços

### Aplicação
- Spring Boot API
- Porta 8080

### Banco de Dados
- PostgreSQL
- Porta 5432

---

## Pipeline CI/CD

A pipeline automatiza:
- Build da aplicação
- Validação da estrutura
- Containerização Docker

---

## Docker Compose

O Docker Compose realiza a orquestração dos serviços:
- Aplicação
- Banco PostgreSQL

---

## Arquitetura Cloud

A solução foi planejada para execução em ambiente cloud utilizando Microsoft Azure Virtual Machines.

---

## Execução Local

```bash
docker compose up