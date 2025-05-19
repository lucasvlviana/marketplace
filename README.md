# Desafio Prático - Marketplace MBA

O projeto é um site desktop de gestão de produtos de venda em marketplace, com dashboard e listagem de produtos.
Esse é um dos desafios prático do MBA Full-Stack, um dos conteúdos disponíveis para alunos da Rocketseat.

## Setup

- Realize o clone/download desse repositório;
- Acesse pelo terminal a pasta do projeto;
- Instale as dependências com `npm i`
- Inicie o banco e execute a seed com `npx prisma migrate dev`
- Inicie a aplicação com `npm run start:prod`

## Dicas

1. Caso queira verificar tanto as tabelas quanto os dados registrados no banco, você pode utilizar a interface visual Prisma Studio. Para utilizá-la, basta executar `npx prisma studio` no terminal.

2. Caso tenha problemas com os dados registrados no banco e precise restaurá-lo, execute o comando `npx prisma migrate reset` e confirme a operação com `Y`.

## Documentação

Você encontra a documentação completa desse desafio no link abaixo:

https://rocketseat-mba-marketplace.apidocumentation.com/reference