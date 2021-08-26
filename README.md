
## Index
- [Projeto](#-projeto)
- [Layout](#-layout)
- [Tecnologias](#rocket-tecnologias)
- [Como executar o projeto](#-como-executar-o-projeto)
- [Como contribuir](#-como-contribuir)
- [Licença](#memo-licença)
- [Autor](#-autor)


## 💻 Projeto

Projeto desenvolvido no **GoStack** da **Rocketseat**.

## :rocket: Tecnologias
O projeto foi desenvolvido utilizando as seguintes tecnologias:
- [TypeScript](https://www.typescriptlang.org)
- [PostgreSQL](https://www.postgresql.org)
- [TypeORM](https://typeorm.io)
- [Docker](https://www.docker.com)
- [Redis](https://redis.io)
- [MongoDB](https://www.mongodb.com)
- [Jest](https://jestjs.io)
- [NodeJS](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)

## 🚀 Como executar o projeto

Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina:
[Git](https://git-scm.com), [Docker](https://www.docker.com), [DBeaver](https://dbeaver.io), [Node.js](https://nodejs.org/en/).

#### Instalação e configuração do Docker

1. Instale o [docker](https://www.docker.com/get-started) em sua máquina.
2. Crie um contêiner postgres no terminal docker: ``docker run --name postgres -e POSTGRES_PASSWORD = docker -p 5432: 5432 -d postgres``.
3. Inicie o container criado: ``docker start postgres``.

### 🎲 Executando o Back End (servidor)

```bash

# Clone este repositório

# Instalar dependências
$ yarn

# Abra o DBeaver e crie uma nova conexão, inserindo os dados:
# HOST: localhost
# DATABASE: Postgres
# USERNAME: Postgres
# PASSWORD: docker

# Instale todas as dependências do banco de dados
$ yarn typeorm:migration: run

# Execute o aplicativo em modo de desenvolvimento
$ yarn dev:server

# O servidor irá iniciar na porta: 3333 - vá para http://localhost:3333

```

