backend

fastify
prisma
banco de dados SQLITE
diagrama ERD
Contagem de botões

dependencia tsx para transpilar TS para JS

`npm i tsx -D`

script para executar ts
"dev": "tsx src/server.ts"

flag watch para monitorar as mudanças automaticamente
"dev": "tsx watch src/server.ts"

comando utilizado para gerar as migrations do prisma DB
` npx prisma migrate dev`

visualizar o banco pelo browser
`npx prisma studio`

Mermaid JS
criação de diagramas através de código

`npm i prisma-erd-generator @mermaid-js/mermaid-cli -D`

comando para executar o diagrama
`npx prisma generate`

CORS:
`npm i @fastify/cors`
