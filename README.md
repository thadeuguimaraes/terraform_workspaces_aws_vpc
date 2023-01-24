# Terraform_workspaces_aws_vpc

Este projeto consiste em criar um ambiente de VPC (Virtual Private Cloud) na AWS (Amazon Web Services) com dois ambientes: Prod e Dev.

## Arquivos

- `main.tf`: arquivo principal do Terraform que contém as configurações gerais do projeto, como provider e variables.
- `network.tf`: arquivo específico para configurações de rede, como subnets e security groups.

## Ambientes

- `Prod`: ambiente de produção, com configurações de segurança mais rigorosas e recursos de alta disponibilidade.
- `Dev`: ambiente de desenvolvimento, com configurações menos restritivas e recursos suficientes para testes e desenvolvimento
