# Projeto base para o evento Bootcamp Imersão AWS com Docker

## Para rodar as migrations no container

``` cmd
docker-compose exec server bash -c 'npx sequelize db:migrate'
```
