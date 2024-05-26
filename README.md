# BuyNowAPI

BuyNowAPI é uma API de e-commerce robusta e escalável, desenvolvida com NestJS e TypeScript, que utiliza padrões de projeto como Repository para abstrair a lógica de acesso ao banco de dados e Strategy para suportar múltiplos métodos de pagamento.

## Funcionalidades

- Gerenciamento de produtos (CRUD)
- Integração com múltiplos métodos de pagamento (Cartão de Crédito, PayPal, etc.)
- Utilização de padrões de projeto para melhorar a escalabilidade e manutenção do código

## Tecnologias Utilizadas

- [NestJS](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [TypeORM](https://typeorm.io/) (ou outra biblioteca de ORM de sua escolha)
- [Jest](https://jestjs.io/) (para testes)

## Padrões de Projeto Implementados

- **Repository**: Abstração da lógica de acesso ao banco de dados.
- **Strategy**: Implementação de diferentes métodos de pagamento.

## Pré-requisitos

- Node.js (v14 ou superior)
- npm

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/oatiliohector/buyNowAPI

cd buyNowAPI
```

2. Instale as dependências:
```bash
npm install
````

2. Inicie o servidor de desenvolvimento:
```bash
Copy code
npm run start:dev
```

A API estará disponível em http://localhost:3000.