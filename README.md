# Project Panel
Site de anotações de filmes e séries

## Pré-requisitos:
    - Node.js 18+ - https://nodejs.org/en/download/package-manager

## Baixando o projeto:
    - Este repositório contém dois submódulos contendo o Front-end e Back-end do projeto, para baixar o projeto completo utilize o comando abaixo 
    - git clone --recurse-submodules https://github.com/PatrickCosta7/ProjectPanel_MonoRepo.git 

## Subindo o projeto com Docker:
    - Certifique-se que você tenha em sua máquina o Docker desktop ou somente o deamon instalado: https://docs.docker.com/engine/install/
    - `$ docker compose up` -> Cria as imagens e os containers contendo a aplicação completa
    - Acesse o projeto via `http://localhost:3000`

## Subindo o projeto localmente:
    - Através do terminal, digite os comandos abaixo:

    - `$ cd project_panel_API/` -> acessa a pasta da API
    - `$ npm install` -> Instala todas as dependências do projeto
    - `$ nodemon app.js` -> Comando para rodar o projeto`em: `http://localhost:8001/`

    - Com a API funcionando, em seguinda digite:
    - `$ cd ../project-panel/` -> Acessa a pasta do front
    - `$ npm install` -> Instala todas as dependências do projeto
    - `$ npm start` -> Inicia o projeto
    - Acesse link `http://localhost:3000`
