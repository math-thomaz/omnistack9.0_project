# Projeto Omnistack 9.0 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/math-thomaz/omnistack9.0_project/blob/master/LICENSE) 

# Sobre o projeto

Parte do evento Omnistack, autoria da instituição de ensino Rocketseat, onde foram apresentados conceitos sobre back-end, front-end e mobile. A parte web (front-end) traz a ideia de registro de spots, termo utilizado para referir-se a um ponto de encontros como empresa ou instituição de ensino. A aplicação consiste em uma tela onde o usuário insere seu email e cadastra seu spot. Neste formulário, temos campos para adicionar uma imagem, listar tecnologias/linguagens usada neste spot, e o preço cobrado por dia. A intenção por trás disto seria integrar com uma aplicação mobile, onde o usuário faria uma busca através das tecnologias/linguagens de seu interesse e agendasse uma data para realizar este encontro.

## Aspectos Técnicos (Front end)
Para o desenvolvimento, foi utilizado o combo Javascript (ES6) + React. Utilizamos conceitos de estados para guardar os spots com React Hooks (useState, useEffect e useMemo), React Router Dom para paginação entre telas e requisições à API com Axios.

## Layout web
![Web 1](https://github.com/math-thomaz/assets/blob/master/Rocketseat/omnistack9.0_project/img1.PNG)

![Web 2](https://github.com/math-thomaz/assets/blob/master/Rocketseat/omnistack9.0_project/img2.PNG)

![Web 3](https://github.com/math-thomaz/assets/blob/master/Rocketseat/omnistack9.0_project/img3.PNG)

# Tecnologias utilizadas
## Back end
- JS
- NodeJS
- Express
- Sequelize
- Yup

## Front end
- CSS / JS (ES6)
- ReactJS
- Axios
- React Hooks

## Mobile
- Javascript
- React Native
- Expo

# Como executar o projeto

```bash
## Back end
Pré-requisitos: npm / yarn / Insomnia

## Entre na pasta do projeto back end:
cd backend

## Instale as dependências:
yarn install

## Execute o projeto:
yarn dev

## Front end web
Pré-requisitos: npm / yarn

## Entre na pasta do projeto front end web:
cd frontend

## Instale as dependências:
yarn install

## Execute o projeto:
yarn start
```
