# Gestão de Campanhas Astrazeneca - AssistCare

Integrating REACT (gem 'react_on_rails') and RAILS 5.2

## Ruby version: 

* 2.4.2 

## System dependencies

* rails 5.2.0

## Configuration
```sh
 $ bundle install
```

```sh
 $ rails webpacker:install
```

```sh
 $ rails webpacker:install:react
```

### We should now see the following in our terminal:

```sh
 $ Webpacker now supports react.js 🎉
```
```sh
 $ yarn add react-dom react-on-rails
```
```sh
 $ yarn add axios
```
```sh
 $ yarn install
```

## Database creation
```sh
 $ rails db:create
```
```sh
 $ rails db:migrate
```
## Database initialization
```sh
 $ rails db:seed
```
## How to run the test suite

## Deployment instructions

### Deploy Heroku

1. Primeiro (via heroku Cli) criamos APP no heroku. Rode no console no diretório do projeto:
```sh
 $ heroku create app-name
```
2. Agora vamos incluir os buildpacks, que são os pacotes que vão ajudar o heroku a instalar nossas dependências:
```sh
 $ heroku buildpacks:add heroku/ruby
```
* *Se você fizer o deploy sem ‘setar’ o buildpack, o heroku vai detectar qual é o seu framework principal e vai ‘setar’ para você, neste caso o buildpack do ruby.*

3. Para finalizar basta rodar os comandos para subir o código:

```sh
 $ git add .
```
```sh
 $ git commit -m 'My first commit'
```
```sh
 $ git push heroku master
```

## Todos

 - Write MORE Tests


License
----

MIT (change)