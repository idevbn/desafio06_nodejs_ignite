<h1 align="center">
  <strong>Desafio do Bootcamp Ignite da <a href="https://rocketseat.com.br/"><em>Rocketseat</em></a></strong>  
</h1>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white">
  <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
</div>

<br>

<div align="center">
  <a href="#about"><em>Sobre</em></a> • <a href="#techs"><em>Tecnologias</em></a> • <a href="#run"><em>Executando o projeto</em></a>
</div>

<br>

<a id="about"></a>

## :bulb: Sobre

<h3>Esse repositório contém a solução do desafio 6 do Ignite da <em>Rocketseat</em>.
O desafio envolve a realização de consultas no banco de dados com o <em><a href="https://typeorm.io/">TypeORM</a></em> de três maneiras:

- Usando o ORM
- Usando Query Builder
- Usando Raw Query
</h3>

<br>

<a id="techs"></a>

## :computer: Tecnologias

Algumas das tecnologias presentes na solução do desafio:

- [NodeJS](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Docker](https://www.docker.com/)
- [TypeORM](https://typeorm.io/)
- [Jest](https://jestjs.io/)
- [Yarn](https://yarnpkg.com/)

<br>

<a id="run"></a>

## :memo: Executando o projeto

1. Pré-requisitos:

Para executar essa aplicação localmente é necessário ter instalado na sua máquina: **[Node.js](https://nodejs.org/en/)**, **[Git](https://git-scm.com/)** e um gerenciador de pacotes, tal qual: **[Yarn](https://yarnpkg.com/)**.

Também é necessário ter instaldo na máquina o <a href="https://docs.docker.com/desktop/windows/install/"><em>Docker</em></a>.

2. Clonando este repositório:

```sh
  $ git clone https://github.com/idevbn/desafio06_nodejs_ignite
```

3. Executando localmente:

```sh
  # Instalando pacotes e dependências
  $ yarn

  # Criando um container do docker rodando o Postgres com o comando
  $ docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

  # Para parar a execução do container
  $ docker stop ignite-challenge-database-queries

  # Caso deseje o container rodando novamente
  $ docker start ignite-challenge-database-queries
```
