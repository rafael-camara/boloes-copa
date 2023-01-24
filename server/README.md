## 🚀 Como executar

- Instale os pacotes com `yarn`.
  ```bash
  $ yarn
  ```
- Faça uma copia do arquivo `.env.example` para `.env` e altere caso necessário.
  ```bash
  $ cp .env.example .env
  ```
- Execute as migrations. (Esse comando também já vai executar as seeds)
  ```bash
  $ npx prisma migrate dev
  ```
- Inicie o servidor.
  ```bash
  $ yarn dev
  ```