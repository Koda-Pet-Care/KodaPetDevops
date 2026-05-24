# Cloud Deploy Strategy

A solução KodaPet foi planejada para execução em ambiente cloud utilizando Microsoft Azure.

## Estrutura planejada

- Azure Virtual Machine
- Docker Containers
- PostgreSQL Database
- GitHub Actions CI/CD

## Fluxo de Deploy

GitHub → Pipeline CI/CD → Docker Build → Azure VM → Aplicação

## Benefícios

- Escalabilidade
- Automação
- Padronização
- Facilidade de deploy
- Infraestrutura moderna

## Evidência de Execução em Cloud

A aplicação foi implantada em uma máquina virtual Linux na Microsoft Azure.  
A VM foi acessada via SSH, o repositório foi clonado do GitHub e os serviços foram executados utilizando Docker Compose.

Comando utilizado:

```bash
docker compose up -d