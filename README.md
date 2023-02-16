# Ignite Call

Projeto para aprendizado de utilização do BackEnd no Next, prisma no banco de dados e autenticação.

## Um aplicativo para agenda de reuniões no Google Meet.

Para testar o app, basta usar o link abaixo:
https://ignite-call-flax.vercel.app/

## Stack utilizada

**Front-end:** React, React Hook Form, Zod, Radix-ui, axios, stitches, Next, Next Auth e Prisma.

Para codar o projeto, são necessárias 5 variáveis ambiente:

- GOOGLE_CLIENT_SECRET: Retirada de um app do Google, é necessário ter um pra rodar o projeto.
- GOOGLE_CLIENT_ID: Mesma coisa do que a chave acima.
- NEXTAUTH_URL: URL do app em si, usada como callback das funções de autenticação.
- DATABASE_URL: URL do banco de dados.
- NEXTAUTH_SECRET: Chave aleatória usada no processo de autenticação.
