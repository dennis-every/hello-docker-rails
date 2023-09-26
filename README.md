# README

## Description
- A quick demo to create a Rails 7 app with PostgreSQL
- Dockerize this app by adding the Dockerfile and docker-compose.yml files
- Run docker-compose up

### Steps to recreate:
- `rails new hello-docker-rails --database=postgresql`
- `cd hello-docker-rails`
- `rails g scaffold Post title body:text`
- Add Dockerfile included in this repo
- Add docker-compose.yml included in this repo
- `docker-compose up`
