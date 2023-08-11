# [Backstage](https://backstage.io)

### Requisitos:

* nodejs (versão 16 ou 18)
* yarn


### Configuração

Para configurar o app, crie um arquivo `.env` com o template disponível em `.env.example`.
Será necessário gerar um github PAT para a execução.


### Build e execução

Execute os comandos abaixo numa shell para buildar e executar o projeto

```sh
yarn install --frozen-lockfile
yarn tsc
yarn build:backend --config ../../app-config.yaml
docker compose build
docker compose up
```
