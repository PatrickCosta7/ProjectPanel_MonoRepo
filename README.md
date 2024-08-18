# Project Panel
Site de anotações de filmes e séries

## Baixando o projeto:
Este repositório contém dois submódulos contendo o Front-end e Back-end do projeto, para baixar o projeto completo utilize o comando:

    git clone --recurse-submodules https://github.com/PatrickCosta7/ProjectPanel_MonoRepo.git 

## Subindo o projeto com Docker:

Certifique que você tenha em sua máquina o Docker engine instalado e rodando: [Baixar Docker Engine](https://docs.docker.com/engine/install/)

Baixe o projeto, acesse sua pasta pelo terminal e digite o comando:

    Docker compose up

Abra [http://localhost:3000](http://localhost:3000) em seu navegador para visualizar o projeto.

## Subindo o projeto localmente:

Será necessário ter Node.js (versão 18 ou superior) instalado em sua máquina: [Baixar Node.js](https://nodejs.org/en/download/package-manager)

Através do terminal, digite os comandos abaixo:

    cd project_panel_API/ -> acessa a pasta da API

    npm install -> Instala todas as dependências do projeto

    node app.js -> Comando para rodar o projeto`em: `http://localhost:8001/`

Com a API funcionando, digite:

    cd ../project-panel/ -> Acessa a pasta do Front-end

    npm install -> Instala todas as dependências do projeto

    npm start -> Inicia o projeto

Abra [http://localhost:3000](http://localhost:3000) em seu navegador para visualizar o projeto.
