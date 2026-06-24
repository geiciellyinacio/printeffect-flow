# PrintEffect Flow

Sistema web para controle de pedidos, etapa de design gráfico, produção final, financeiro operacional, estoque e dashboard.

## Status do projeto

Em desenvolvimento.

Este projeto está sendo construído como um sistema real de gestão interna para organizar o fluxo de pedidos entre os setores da empresa.

## Objetivo

O objetivo do PrintEffect Flow é substituir controles manuais, anotações em papel e comunicação informal por um sistema centralizado, permitindo acompanhar pedidos, etapas de produção, atrasos, capacidade dos setores, estoque e informações operacionais.

## Problema identificado

Atualmente, a comunicação entre comercial, design gráfico e produção final pode acontecer de forma manual, por conversa direta ou anotações. Isso dificulta o acompanhamento dos pedidos, a identificação de atrasos e a visualização da quantidade de demandas em cada etapa.

## Solução proposta

O sistema permitirá que os pedidos sejam cadastrados pelo comercial e acompanhados durante todo o fluxo:

- Cadastro do pedido
- Envio para etapa de design gráfico
- Envio para produção final
- Marcação de pedido pronto
- Aviso ao cliente pelo comercial
- Acompanhamento de atrasos
- Visualização de quantidades por etapa
- Controle operacional de estoque
- Consulta financeira operacional
- Login com perfis por setor

## Stack planejada

### Backend

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Security
- Validation
- PostgreSQL
- Maven

### Frontend

- React
- TypeScript
- Vite
- React Router
- Axios ou Fetch

### Banco de dados

- PostgreSQL

### Ferramentas

- Git
- GitHub
- VS Code
- Postman
- Docker futuramente

## Módulos planejados

- Comercial
- Design gráfico
- Produção final
- Dashboard
- Financeiro operacional
- Estoque
- Usuários e permissões
- Documentação

## Autenticação e permissões

O sistema terá uma tela única de login. Após o login, cada usuário será redirecionado para o painel correto conforme seu perfil.

Perfis planejados:

- ADMIN/GESTAO
- COMERCIAL
- DESIGN_GRAFICO
- PRODUCAO_FINAL
- FINANCEIRO_OPERACIONAL
- ESTOQUE

## Organização inicial do repositório

```text
printeffect-flow/
├── backend/
├── frontend/
├── docs/
├── README.md
└── LICENSE