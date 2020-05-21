# MasterClass sobre GraphQl

Nessa masterclass foi montada uma pequena aplicação com graphql no backend e react no front, mas o foco da mesma está no graphql.


# Estrutura de diretórios

**server**: representa o **backend** da aplicação.

**client**: representa o **frontend** da aplicação.

```
masterClass
  server
  client
```

Cada pasta agrupa dados por **feature** e não por **tipo**.

Logo, a pasta `perfil` acima agrupa tudo o que é relacionado a perfil, como entidade, service, resolvers, telas e etc.


# Início do desenvolvimento

Executar o comando no banco de dados para criar o schema:

```sql
CREATE SCHEMA `guia` DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci;
```

## Backend (server)

Esses comandos devem ser executados na pasta `server`.

Instalar pacotes do projeto:

```
npm install
```


Executar comando:

```
node server.js
```
Esse comando vai iniciar o servidor.

## Frontend

Esses comandos devem ser executados na pasta `client`.

Instalar pacotes do projeto:

```
npm install
```

Executar comando:

```
npm run start
```

Esse comando vai iniciar o servidor.

# Observação
- Importar o banco de dados para uso
- mudar a porta do servidor de banco de dados para a porta que está configurada na sua máquina. O arquivo está na pasta "/server/src/config"
