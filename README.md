
# API - Escola de Inglês :writing_hand: :woman_teacher:

## Sobre o projeto :open_book:

API desenvolvida durante a trilha de estudos da Alura,onde apliquei os conhecimentos adquiridos sobre, NodeJs, Express e Sequelize, juntamente com arquitetura MVC.O objetivo era criar uma API com um banco de cadastro para alunos e docentes da escola, podendo ser feito atualização,adição, exclusão e listagem de cadastros.

## Feito com :rocket:

- [NodeJS](https://nodejs.org/en/) - Utilizado para rodar o Javascript no back-end.
- [ExpressJS](https://expressjs.com/pt-br/) - Framework usado para contolar as requisições e respostas. 
- [Sequelize](https://sequelize.org/) - Orm para banco de dados relacionais.
- [MySQL](https://www.mysql.com/) - Banco de dados relacional.

## Pre-requisitos :gear:

Você precisa ter instalado: 

```
Node, Npm e MySQL
```

Para instalar consulte: 
* [Node](https://nodejs.org/en/)
* [MySQL](https://dev.mysql.com/downloads/mysql/)

Na sequência crie um banco de dados:

```
create database escola_ingles; 
```
para saber mais [consulte](https://www.devmedia.com.br/primeiros-passos-no-mysql/28438) 

### Baixando e configurando o projeto :open_file_folder:

```
git clone git@github.com:Joely-Brito/API-escola-ingles.git
```
Depois:
```
cd API-escola-ingles/
```
Na sequencia, instale as dependências
```
npm install
```

No arquivo de configuração (api/config/config.json), coloque o seu usuário e senha do MySQL no objeto "development".

**Criando Tabelas no banco de dados:**

No terminal rode:

```
npx sequelize-cli db:migrate  
```

**Populando as tabelas:**

No terminal rode:

```
npx sequelize-cli db:seed:all
```

## Rodando a API :rocket:

Para rodar a API utilize o comando

```
npm start
```


<div align="center">
   Feito com amor, por: <a href="https://www.linkedin.com/in/joely-brito/" target="_blank">Joely Brito</a> ❤️
</div>