![alt text](https://github.com/augustoleandro/fastfeet/blob/master/.github/logo-readme.png?raw=true)

# Desafio Final - GoStack 10 - RocketSeat

## 🚀 Introdução
___
Esta é minha solução do desafio final proposto pela [RocketSeat](https://rocketseat.com.br/). A aplicação FastFeet é uma solução para gestão e entregas de encomendas para um transportadora fictícia.

A solução é composta pelo desenvolvimento do back-end, front-end web e mobile (iOS).
Nessa solução foram utilizadas as seguintes tecnologias [NodeJS](https://nodejs.org/en/), [ReactJS](https://reactjs.org/) e [React Native](https://reactnative.dev/).

O desenvolvimento do desafio final é resultado da conclusão de quatro etapas parciais:

+ [Etapa 1](https://github.com/Rocketseat/bootcamp-gostack-desafio-02)
+ [Etapa 2](https://github.com/Rocketseat/bootcamp-gostack-desafio-03)
+ [Etapa 3](https://github.com/Rocketseat/bootcamp-gostack-desafio-09)
+ [Etapa 4](https://github.com/Rocketseat/bootcamp-gostack-desafio-10)

## 🧑🏻‍💻 Instruções para Instalação e Execução da aplicação
___

👥 Faça um clone do repositório, pegue o seu café ☕️ e vamos lá:

### 1) 🖥 Backend

- Para facilitar os testes na solução de backend clicar no botão seguinte;

   [![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=FastFeet%20API&uri=https%3A%2F%2Fgithub.com%2Faugustoleandro%2Ffastfeet%2Fblob%2Fmaster%2FInsomnia.json)
- Entre na pasta raiz `node` e execute o comando `yarn` para instalar as dependências;
- Renomeie o arquivo `.env.example` para `.env` e preencha as variáveis de ambiente que você utiliza;
- Execute o comando `yarn sequelize db:migrate` para executar as migrations (essa etapa considera que o banco de dados já esteja operacional na sua máquina);
- Execute o comando `yarn sequelize db:seed:all` para criar a conta de usuário administrador no banco de dados;
- Entre na pasta raiz `node` e digite `yarn dev` para rodar a aplicação `node server`;
___
### 2) 💻 Web
  - Entre na pasta raiz `web` e execute o comando `yarn` para a instalação das dependências;
  - Execute o comando `yarn start` para iniciar a aplicação `web`;
___
### 3) 📱 Mobile (iOS)

- Essa aplicação foi desenvolvida primeiramente apenas para dispositivos iOS. Para executar a aplicação você precisa de uma máquina Mac 🍎;
- Entre na pasta raiz `mobile` e execute o comando `yarn` para a instalação das dependências;
- Execute o comando `yarn react-native run-ios` para rodar no Simulator do Mac;
- Você pode testar também em um dispositivo iPhone. Para isso siga essas [instruções](https://reactnative.dev/docs/running-on-device).

___

🧑🏻‍💻 Coded by [Leandro Augusto](https://br.linkedin.com/in/leandroaugustoribeiro)!



