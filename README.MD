# f1-minimal-api

API mínima para expor dados de Fórmula 1 de forma simples e leve.

## Descrição
f1-minimal-api é uma API REST minimalista que fornece informações relacionadas à Fórmula 1 — por exemplo, pilotos, equipes, corridas e resultados — de maneira simples e fácil de integrar em aplicações cliente.

## Tecnologias
- Plataforma / linguagem: `< Node.js | Typescript )>`
- Dependências principais: `< Fastify | @Fastify/cors | tsx  | tsup >`

## Funcionalidades
- Endpoints para listar e consultar entidades relacionadas à F1 (pilotos e equipes).

## Pré-requisitos
- Instale `Node.js > 16`

## Instalação e execução

Node.js
```bash
# instalar dependências
npm install

# executar
npm run start:dev
`


## Endpoints principais (exemplos)

- GET /api/drivers
  - Lista todos os pilotos
  - Exemplo: `curl http://localhost:3333/api/drivers`

- GET /api/drivers/{id}
  - Retorna dados de um piloto específico
  - Exemplo: `curl http://localhost:3333/api/drivers/44`

- GET /api/teams
  - Lista equipes
  - Exemplo: `curl http://localhost:3333/api/teams`




## Licença
Este projeto está sob a licença `<MIT>`.

---
