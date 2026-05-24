# KodaPet DevOps

Projeto desenvolvido para a disciplina **DevOps Tools & Cloud Computing**, com foco na aplicação de práticas DevOps na plataforma **KodaPet**, uma solução voltada ao acompanhamento preventivo e contínuo da saúde de pets.

O objetivo deste repositório é demonstrar a estrutura de infraestrutura, containerização, versionamento, pipeline CI/CD e deploy em ambiente cloud utilizando **Docker**, **Docker Compose**, **GitHub Actions** e **Microsoft Azure**.

---

##  Sobre o Projeto

A plataforma KodaPet tem como proposta conectar tutores, clínicas veterinárias e dados de saúde dos pets em um ecossistema digital preventivo.

Na parte de DevOps, o foco foi estruturar um ambiente capaz de:

- padronizar a execução da aplicação;
- containerizar os serviços;
- executar banco de dados em container;
- automatizar build com pipeline CI/CD;
- versionar o projeto no GitHub;
- realizar execução em ambiente cloud com Azure VM.

---

##  Objetivo da Entrega DevOps

Aplicar práticas DevOps modernas para preparar a aplicação para execução em ambiente padronizado, escalável e automatizado.

Principais objetivos:

- Criar um ambiente com Docker;
- Utilizar Docker Compose para orquestração;
- Executar banco PostgreSQL em container;
- Configurar pipeline CI/CD com GitHub Actions;
- Utilizar GitHub para versionamento;
- Criar uma VM Linux na Azure;
- Clonar o repositório na VM;
- Executar os containers em ambiente cloud.

---

##  Tecnologias Utilizadas

| Tecnologia | Finalidade |
|---|---|
| Docker | Containerização da aplicação |
| Docker Compose | Orquestração dos containers |
| PostgreSQL | Banco de dados containerizado |
| Git | Controle de versão local |
| GitHub | Repositório remoto e colaboração |
| GitHub Actions | Pipeline CI/CD |
| Microsoft Azure | Ambiente cloud |
| Ubuntu Server | Sistema operacional da VM |
| Java 17 | Ambiente base da aplicação |
| Spring Boot | API planejada da solução |

---

##  Estrutura do Repositório

```bash
KodaPetDevops/
│
├── .github/
│   └── workflows/
│       └── ci-cd.yml
│
├── target/
│   └── app.jar
│
├── Dockerfile
├── docker-compose.yml
├── cloud-deploy.md
├── README.md
└── .gitignore

---

## Desenvolvido por:
Evellyn Barbosa Ferreira - Rm562744
Henrique Sinkevicius Maran - Rm562977
Maicon Douglas da Silva Timoteo - RM561279 

## Link do youtube:

