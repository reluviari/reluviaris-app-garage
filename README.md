<h1 align="center">
  <strong>Integrating REACT and RAILS</strong>
</h1> 

<p align="center">
  Integrating REACT (gem 'react_on_rails') and RAILS 5.2
</p> 

## 📌 Link to App

You can visit the app by clicking this link: [Access App](https://todocartoes-danilo-challenge.herokuapp.com/).

## Link to Tutorial

You can visit the tutorial by clicking this link: [Access Tutorial](https://cognitiveclass.ai/blog/react-on-rails-tutorial-integrating-react-and-ruby-on-rails/).

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

* *Agora devemos ver o seguinte em nosso terminal.*

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

## 🙋‍♂️ Author

* **Danilo Dias** - [reluviari](https://github.com/reluviari)
