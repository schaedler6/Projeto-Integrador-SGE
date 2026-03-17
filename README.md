# Projeto Integrador SGE

Sistema web de gestão de estoque desenvolvido para controle de produtos, usuários e auditoria de movimentações internas.

O projeto foi construído com Python e Flask no back-end, MySQL no banco de dados e HTML, CSS e JavaScript no front-end. A aplicação foi pensada para centralizar o gerenciamento de estoque, melhorar a rastreabilidade das operações e organizar o fluxo de acesso e movimentação dentro do sistema.

## Objetivo

O objetivo deste projeto é oferecer uma base funcional para controle de estoque em ambiente web, permitindo:

- cadastro e gerenciamento de produtos
- controle de usuários e permissões
- registro de movimentações
- rastreabilidade e apoio à auditoria
- organização das operações do sistema

## Funcionalidades

- cadastro, edição e consulta de produtos
- controle de acesso por usuários
- histórico de movimentações
- estrutura preparada para testes automatizados
- integração com pipeline de validação contínua

## Tecnologias Utilizadas

- Python
- Flask
- MySQL
- HTML
- CSS
- JavaScript
- Git
- GitHub Actions

## Qualidade e Automação

O repositório utiliza validações automatizadas para manter consistência no código, incluindo:

- formatação com Black
- análise estática com Ruff
- testes com Pytest
- execução automática via GitHub Actions

## Estrutura do Projeto

```text
Projeto-Integrador-SGE/
├── docs/
├── tests/
├── .github/
├── requirements.txt
├── pyproject.toml
└── README.md
