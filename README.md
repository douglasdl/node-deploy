Create the project (package.json):
```sh
npm init -y
```

Install the dependencies:
```sh
npm i fastify
npm i @prisma/client
npm i zod
```

Install the development dependencies:
```sh
npm i -D typescript @types/node tsx tsup
npm i prisma -D
```

Create the tsconfig.json (change the "target": "es2020",):
```sh
npx tsc --init
```

Create the prisma:
```sh
npx prisma init
```
Create the model in the schema.prisma.

## Docker

List the running containers:
```sh
docker ps
```
Stop the running container (informing the Container ID):
```sh
docker stop 123456789012
```

Start the local Postgres:
```sh
docker start pg
```

Run the prisma migrations:
```sh
npx prisma migrate dev
```

Open the Prisma Studio to see and edit the database:
```sh
npx prisma studio
```

Run the project:
```sh
npm run dev
npm run test
npm run build
npm run start
```

## Git

Init the git repository:
```sh
git init
```