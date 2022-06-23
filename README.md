<h1 align="center">
      <a href="#" alt=> Hackathon de Inovação e Tecnologia </a>
</h1>


<h3 align="center">
     Hackathon Iblue desenvovido pelos estágiarios.
</h3>


    
    

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Regras de negócio](#-regras-de-negocio)
   * [Funcionalidades](#-funcionalidades)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Rodando a aplicação web (Frontend)](#user-content--rodando-a-aplicação-web-frontend)
     * [Tecnologias](#-tecnologias)
     * [Website](#user-content-website--react----typescript)
     * [Server](#user-content-server--nodejs----typescript)
<!--te-->



## 💻 Sobre o projeto

🏫 Simulador de Bônus -  É uma solução para fazer o acompanhamento das metas e fazer a simulação do bônus anual para os Ibluers.

 
##    🖥️ Regras de negócio
####  🧍  A aplicação deve redirecionar o usuário para uma página inicial com e-mail e senha;
####  🧍  A aplicação deve retornar uma mensagem para caso aja erro no sistema;
####  🧍  O usuário deve utilizar um e-mail válido;
####  🧍  O usuário deve utilizar uma senha com mais de 6 caracteres;
####  🧍  Todos campos de registro e login do usuário deve ser obrigatório;
####  🧍  O usuário esqueceu a senha deve digitar o código;
####  🧍  O usuário deve digitar a nova senha 2 vezes e confirmar;
####  🧍  O usuário pode clicar na tag cadatrar metas;


## ⚙️ Funcionalidades

- [x] Os colaboradores podem se cadastrar na aplicação usando:
  - [x] um e-mail válido
  - [x] uma senha válida

- [x] Os colaboradores podem cadastrar suas metas individuais:
  - [x] usando a tag cadastrar

- [x] Os gestores podem consultar a visão individual:
  - [x] podem visualizar as metas globais,metas setoriais,e metas individuais;
  - [x] podem cadastrar novas metas;
  - [x] podem fazer simulações de cada colaborador ;





## 🚀 Como executar o projeto

Este projeto foi dividido em varias partes, para poder ser execultado :
1. Frontend

💡 O Frontend para funcionar precisa ser execultado.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).[ Vue.js](https://vuejs.org/), Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).


## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Website**  ([Vue](https://vuejs.org/))

-   **[Quasar](https://quasar.dev/)**
-   **[Axios](https://axios-http.com/ptbr/docs/intro)**
-   **[vue-router](https://router.vuejs.org/)**

#### **Server** ([NodeJS](https://nodejs.orgen/))

-   **[mysql2](https://github.com/mapbox/node-sqlite3)**
-   **[sequelize](https://sequelize.org/)**
-   **[nodemon](https://github.com/TypeStrong/ts-node)**


#### **Utilitários**

-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)**



#### 🧭 Rodando a aplicação web (Frontend)

```bash
# Clone este repositório
$ git clone git@github.com:tgmarinho/README-ecoleta.git
# Acesse a pasta do projeto no terminal/cmd
$ cd iblue-school-front
# Instale as dependências
$ npm install ou yarn install
# Crie um arquivo .env na raiz do projeto
$ touch .env ou crie um arquivo pela IDE
# Vá para o arquivo .env.example
$ copie os dados do .env.example e cole no .env
# Altere os dados do .env 
$ Altere a porta ex: http://localhost:9000
# Execute a aplicação em modo de desenvolvimento
$ npm run serve ou yarn serve
# O servidor iniciará na porta:8080 por padrão - acesse http://localhost:9000
