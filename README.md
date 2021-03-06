<div align="center">
    <img src=".github\logo-ecoleta.svg" width="300px"/>
</div>

<h2 align="center">
   Next Level Week 1.0 | <img alt="badge rocketseat" align="center" src=".github\rocket.svg">
</h2>

<p align="center">
<img alt="badge typescript" src=".github\badge-typescript.svg">
<img alt="badge node" src=".github\badge-node.svg">
<img alt="badge npm" src=".github\badge-npm.svg">
<img alt="badge npm" src=".github\sqlite.svg">
<img alt="badge react" src=".github\badge-react.svg">
<img alt="badge react native" src=".github\rnative.svg">
<img alt="badge react router" src=".github\badge-router.svg">
<img alt="badge react leaflet" src=".github\reactleaf.svg">
<img alt="badge hapi" src=".github\hapi.svg">
<img alt="badge expo" src=".github\expo.svg">
<img alt="badge knexjs" src=".github\knexjs.svg">
<img alt="badge prettier" src=".github\prettier.svg">
<img alt="badge vscode" src=".github\badge-visual_studio_code.svg">
<img alt="badge eslint" src=".github\badge-eslint.svg">
<img alt="badge eslint" src=".github\figma.svg">
</p>

<p align="center">
<img alt="Made by Azevedo Tau" src="https://img.shields.io/badge/made%20by-Azevedo Tau-%20?color=34cb79">
<img alt="Repository size" src="https://img.shields.io/github/repo-size/azevedotau-ai/e-coleta/ecoleta_nlwrocketseat?color=34cb79">
<img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/angelicaalbuquerque/ecoleta_nlwrocketseat?color=34cb79">
</p>

 <p align="center">
  <a href="https://insomnia.rest/run/?label=NLW%201.0%20-%20Ecoleta&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fangelicaalbuquerque%2Fecoleta_nlwrocketseat%2Fmaster%2Fserver%2FInsomnia.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

---

<p align="center">
  <a href="#-next-level-week">Next Level Week</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-rodar-o-projeto">Como rodar o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Entre-em-contato">Contato</a>
</p>

## ???? Next Level Week

<div align="center">
    <img src=".github\logo-next-level-week-1.svg" width="150px"/>
</div>

<p>
Promovido pela <a href="https://rocketseat.com.br/" target="_blank">Rocketseat</a>, a Next Level Week ?? uma experi??ncia online com
muito conte??do pr??tico, muitos desafios e
hacks que auxiliam o desenvolvedor a avan??ar para o pr??ximo n??vel de sua carreira.

A aplica????o deste reposit??rio foi realizada durante a trilha Booster, ministrada por Diego Fernandes (CTO na Rocketseat), desenhada para quem j?? tem
experi??ncia com programa????o e quer
ampliar suas habilidades e melhorar seus projetos.

</p>

## ???? Projeto

<p align="center">
  <img alt="Ecoleta" src=".github\ecoleta-mobile-web.png" width="100%">
</p>

Desenvolvido para promover o Dia Mundial do Meio Ambiente, o Ecoleta ?? um marketplace que ajuda pessoas a encontrarem pontos de coleta de res??duos de forma eficiente.

A aplica????o Web permite que entidades se cadastrem disponibilizando seus dados para contato, al??m de informa????es sobre itens de coleta, enquanto a aplica????o Mobile lista os pontos cadastrados de acordo com o estado e a cidade selecionados pelo usu??rio.

### Web

<p align="center">
  <img alt="Ecoleta" src=".github\Ecoleta.gif" width="80%">
</p>

### Mobile

<p align="center">
  <img alt="Ecoleta" src=".github\ecoleta-mobile.gif" width="40%">
</p>

## ???? Layout

Voc?? pode visualizar o layout do projeto atrav??s [deste link](https://www.figma.com/file/9TlOcj6l7D05fZhU12xWT3/Ecoleta-Booster?node-id=0%3A1) no [Figma](http://figma.com/).

## ???? Como rodar o projeto

### Backend

```bash
# Clone este reposit??rio
$ git clone https://github.com/azevedotau-ai/e-coleta.git

# Acesse o reposit??rio
$ cd e-coleta/server

# Instale as depend??ncias
$ npm install

# Instale as Migrates
$ npm run knex:migrate

# Instale as Seeds iniciais do banco de dados
$ npm knex:seed

# Execute a aplica????o em modo de desenvolvimento
$ npm run dev

# rodando na porta 3333
```

### Front-end

```bash
# Clone este reposit??rio
$ git clone https://github.com/azevedotau-ai/e-coleta.git

# Acesse este reposit??rio
$ cd e-coleta/web

# Instale as depend??ncias
$ npm install

# Execute a aplica????o
$ npm start

# rodando na porta 3000
```

### Mobile

```bash
# Clone este reposit??rio
$ git clone  https://github.com/azevedotau-ai/e-coleta.git

# Acesse este reposit??rio
$ cd e-coleta/mobile

# Instale as depend??ncias
$ npm install

# Execute a aplica????o
$ expo start

# O Expo abrir?? uma nova janela no navegador; escaneie o qrcode no terminal ou na p??gina aberta pelo Expo

# Caso tenha problema com as fontes, execute:
$ expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto

```

## ???? Tecnologias

O projeto foi desenvolvido com as seguintes tecnologias:

<details>
  <summary>Backend</summary>

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Typescript](https://www.typescriptlang.org/)
- [TS-Node-Dev](https://www.npmjs.com/package/ts-node-dev)
- [Celebrate](https://github.com/arb/celebrate)
- [Cors](https://www.npmjs.com/package/cors)
- [Hapi/Joi](https://www.npmjs.com/package/@types/hapi__joi)
- [Multer](https://www.npmjs.com/package/multer)
- [SQLite3](https://www.sqlite.org/index.html)
- [KnexJS](http://knexjs.org/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [VS Code](https://code.visualstudio.com/)
</details>

<details>
  <summary>Frontend</summary>

- [Axios](https://www.npmjs.com/package/axios)
- [Typescript](https://www.typescriptlang.org/)
- [React](https://pt-br.reactjs.org/)
- [React Dropzone](https://github.com/react-dropzone/react-dropzone)
- [React Icons](https://react-icons.netlify.com/#/)
- [React Router](https://www.npmjs.com/package/react-router-dom)
- [React Leaflet](https://react-leaflet.js.org/)
- [Leaflet](https://leafletjs.com/)
- [Expo MailComposer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
- [Expo](https://expo.io/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [VS Code](https://code.visualstudio.com/)

</details>

<details>
  <summary>Mobile</summary>

- [Axios](https://www.npmjs.com/package/axios)
- [Typescript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/learn)
- [Expo Google Fonts](https://github.com/expo/google-fonts)
- [Expo Location](https://docs.expo.io/versions/latest/sdk/location/)
- [Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [React Navigation](https://reactnavigation.org/)
- [React Native Appearance](https://github.com/expo/react-native-appearance)
- [React Native Picker Select](https://www.npmjs.com/package/react-native-picker-select)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [VS Code](https://code.visualstudio.com/)

</details>

## ???? Entre em contato!

<div align="left">
<a href="https://www.linkedin.com/in/azevedo-tau-5325b1170/" target="_blank" >
  <img alt="Linkedin - Azevedo Tau" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a> &nbsp;&nbsp;&nbsp;
</div>

---

<p align="center">
Feito com muito ??? e ???? por Azevedo Tau
</p>

<p align="center">
???? 
</p>
