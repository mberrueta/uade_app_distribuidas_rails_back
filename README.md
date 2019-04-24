# uade_app_distribuidas_rails_back

Example backend in ruby on rails

## Dependencies

- ruby (rvm)
- nodejs
- rails
- docker

## Install (from scratch)

```sh
gem update rails
rails new . app-distribuidas-api --api --database=postgresql
bundle install
# env var to replace connection string things PG_PORT, PG_DATABASE, PG_USER, PG_PASS, PG_HOST
rake db:create db:migrate
rails s

```

## Docker postgres

If you don't have a postgres db create a `docker-compose.yml` as example

```sh
docker-compose up -d
```
