# Blog API

For storing text blurbs

## Needed

- PostgreSQL - https://postgresapp.com/
- Ruby on Rails - https://gorails.com/setup/osx/10.15-catalina

## Install

```
git clone git@github.com:joekennerly/blog-api.git
cd blog-api
cp example.env .env
```

Open `/directory/.env` and enter in your postgres username and password

```
bundle install
rails db:create db:migrate
```

## Run Server

```
rails server --binding=127.0.0.1
```
