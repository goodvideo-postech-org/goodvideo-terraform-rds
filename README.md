# Terraform para Criação de Bancos de Dados no Amazon RDS

Este projeto utiliza o Terraform para provisionar dois bancos de dados PostgreSQL no Amazon RDS. O código cria os seguintes recursos:

1. **Banco de Dados para Usuário**: Um banco de dados PostgreSQL chamado `usuario`, destinado a armazenar informações relacionadas a usuários.
2. **Banco de Dados para Uploads**: Um banco de dados PostgreSQL chamado `upload`, destinado ao armazenamento de arquivos ou dados de upload.

## Pré-requisitos

- **Terraform** instalado. Você pode seguir as instruções de instalação [aqui](https://www.terraform.io/downloads.html).
- **Credenciais AWS configuradas**. Você pode configurar suas credenciais utilizando o AWS CLI ou variáveis de ambiente.

## Estrutura do Projeto

O projeto é composto por uma configuração Terraform (`main.tf`), que define os recursos necessários para provisionar o RDS.
