# KodaPet DevOps

Projeto DevOps desenvolvido para gerenciamento da infraestrutura da plataforma KodaPet.

## Tecnologias Utilizadas

- Docker
- Docker Compose
- PostgreSQL
- GitHub Actions
- Java 17
- Spring Boot

## Estrutura DevOps

O projeto utiliza containers Docker para padronização do ambiente e Docker Compose para orquestração dos serviços.

## Pipeline CI/CD

A pipeline automatiza o processo de build da aplicação utilizando GitHub Actions.

## Serviços

### Aplicação
- Container Spring Boot
- Porta 8080

### Banco de Dados
- PostgreSQL
- Porta 5432

## Execução

```bash
docker compose up
