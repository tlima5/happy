<h1 align="center">
    <img alt="Happy" title="Happy" src="https://raw.githubusercontent.com/rocketseat-education/nlw-03-omnistack/master/.github/logo.svg" />
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#recycle-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#desktop_computer-instalação-e-execução">Instalação e Execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=15C3D6&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=15C3D6&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="Happy" src="https://raw.githubusercontent.com/rocketseat-education/nlw-03-omnistack/master/.github/happy.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

* [Yarn](https://yarnpkg.com/)
* [NodeJs](https://nodejs.org/en/)
* [ReactJs](https://reactjs.org/)
* [React-Native](https://reactnative.dev/)
* [React-Navigation](https://reactnavigation.org/)
* [React-Leaflet](https://react-leaflet.js.org/)
* [MapBox](https://www.mapbox.com/)
* [TypeScript](https://www.typescriptlang.org/)
* [Expo](https://expo.io/)
* [Express](https://expressjs.com/)
* [Multer](https://www.npmjs.com/package/multer)
* [Sqlite3](https://www.sqlite.org/index.html)
* [TypeORM](https://typeorm.io/#/)
* [Yup](https://github.com/jquense/yup)

## :recycle: Projeto

O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz 💜

## :desktop_computer: Instalação e Execução
**Antes de iniciar, é necessário ter o [NodeJs](https://nodejs.org/en/) e o [Yarn](https://yarnpkg.com/) baixado na máquina, bem como o aplicativo [Expo](https://expo.io/) no celular para a aplicação mobile**

### Comando para clonar o repositório: 
```bash
  #Para clonar o projeto
  git clone https://github.com/tlima5/happy
```
### Para rodar a parte do servidor:
```bash
  #Navegar e baixar as depêndencias
  cd backend
  yarn install

  #Configuração
  Criar arquivo .env baseado no modelo .env.example onde
  - SERVER_HOST é onde está rodando a api. Ex:(http://localhost:3333)

  #Iniciar o servidor com yarn
  yarn dev
```

### Para rodar a aplicação web:
```bash
  #Navegar e baixar as depêndencias web
  cd web
  yarn install
  
  #Configuração
  Criar arquivo .env baseado no modelo .env.example onde
  - REACT_APP_MAPBOX_TOKEN é o token MapBox
  - REACT_APP_SERVER_HOST é onde está rodando a api back-end. Ex:(http://localhost:3333)
  
  #Iniciar a aplicação
  yarn start
```
Vá para http://localhost:3333 para acessar o website.

### Para rodar a aplicação mobile:
```bash
  #Navegar e baixar as depêndencias mobile
  cd mobile
  yarn install
  
  #Configuração
  Acessar src/services/api.ts e modificar o baseURL para o ip da máquina
  
  #Iniciar a aplicação
  yarn start
```

## :memo: Licença

Esse projeto está sob a licença MIT.

---

Feito com ♥ by Thiago Lima :wave: Inspirado em Rocketseat e [LarisseLima](https://github.com/LarisseLima)
