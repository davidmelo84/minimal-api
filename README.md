# Minimal API para Registro de Veículos

Este projeto demonstra a criação de uma API minimalista utilizando ASP.NET, voltada para o registro e gerenciamento de veículos, com autenticação JWT para administradores e documentação via Swagger. A aplicação inclui um conjunto completo de testes para garantir a robustez do sistema.

## Funcionalidades

- **Login e Autenticação**
  - Rota de login para validação em memória
  - Autenticação de administradores com validação de login e senha no banco de dados
  - Configuração de token JWT para autenticação
  - Perfis de administrador e editor com autorização personalizada

- **Gerenciamento de Veículos**
  - Configuração do modelo de veículos
  - Rotas para criar, atualizar, deletar e listar veículos
  - Validação ao cadastrar e atualizar veículos
  - Organização das rotas no Swagger por contexto

- **Administrador**
  - Configuração do projeto com Entity Framework e tabela de administradores
  - Seed para cadastrar administrador padrão
  - Endpoints para gerenciamento de administradores

- **Documentação e Testes**
  - Configuração do Swagger para documentação da API e passagem de token JWT
  - Criação de solução (sln) e projeto de testes
  - Testes de unidade para o modelo de Administrador
  - Testes de persistência
  - Testes de request

## Estrutura do Projeto

1. **Configuração Inicial**
   - Criação do projeto utilizando Minimals APIs
   - Entendimento do boilerplate inicial

2. **Configuração de Autenticação e Segurança**
   - Implementação de autenticação JWT
   - Configuração do Swagger para token JWT

3. **Gerenciamento de Dados**
   - Configuração do Entity Framework
   - Seed de dados para administradores

4. **Criação e Validação de Endpoints**
   - Implementação das rotas CRUD para veículos e administradores
   - Validações de entrada e regras de negócios

5. **Testes e Deploy**
   - Desenvolvimento de testes unitários, de persistência e request
   - Preparação e deploy da aplicação

## Deploy

Instruções sobre como realizar o deploy da aplicação estarão disponíveis em breve.

## Como Contribuir

Contribuições são bem-vindas! Para contribuir, siga os passos abaixo:

1. Fork o projeto
2. Crie uma nova branch (`git checkout -b feature/nova-feature`)
3. Faça suas alterações e commit (`git commit -am 'Adiciona nova feature'`)
4. Faça o push para a branch (`git push origin feature/nova-feature`)
5. Crie um Pull Request
