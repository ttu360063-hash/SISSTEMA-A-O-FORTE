# Sistema de Aluguel - AÇO FORTE LTDA

Este é um sistema de aluguel de equipamentos desenvolvido com Node.js/Express para o backend e React para o frontend.

## Pré-requisitos

- Node.js (v14 ou superior)
- PostgreSQL

## Configuração

1. **Backend:**
   - Navegue para o diretório `backend`
   - Execute `npm install` para instalar as dependências
   - Configure o banco de dados PostgreSQL no arquivo `config/database.js`
   - Execute o script SQL em `database.sql` para criar as tabelas
   - Inicie o servidor com `node server.js` ou `npm start`

2. **Frontend:**
   - Navegue para o diretório `frontend`
   - Execute `npm install` para instalar as dependências
   - Inicie o aplicativo com `npm start`

## Funcionalidades

- Gerenciamento de clientes
- Gerenciamento de equipamentos
- Gerenciamento de aluguéis
- Relatórios de faturamento, clientes e estoque

## Endpoints da API

- Clientes: /api/clientes
- Equipamentos: /api/equipamentos
- Aluguéis: /api/alugueis
- Relatórios: /api/relatorios
