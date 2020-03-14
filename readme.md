<h1 align="center">
	<img alt="GoStack" src="src/assets/logo.png" width="200px" />
</h1>

<h3 align="center">
  Projeto ReactNative
</h3>

<p align="center">
  <a href="#-Instalação-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## 📥 Instalação e execução


### Backend

1. A partir da raiz do projeto, entre na pasta do backend rodando `cd backend`;
2. Rode `yarn` para instalar as dependências;
3. Crie um banco de dados no `postgres` com o nome de `gobarber`;
4. Rode `cp .env.example .env` e preencha o arquivo `.env` com **SUAS** variáveis ambiente;
5. Rode `yarn sequelize db:migrate` para executar as migrations;
6. Rode `yarn dev` para iniciar o servidor.

### Frontend Web

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

1. A partir da raiz do projeto, entre na pasta do frontend web rodando `cd frontend`;
2. Rode `yarn` para instalar as dependências;
3. Rode `yarn start` para iniciar o client.

### Frontend Mobile

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

1. A partir da raiz do projeto, entre na pasta do frontend mobile rodando `cd mobile`;
2. Rode `yarn` para instalar as dependências;
3. Rode `yarn react-native run-ios` ou yarn `react-native run-android` dependendo do SO.

## 🤔

---

Feito com ♥ by [Renato](https://www.renatolucena.net)

