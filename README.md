# Docker todolist

# <strong><g-emoji class="g-emoji" alias="man_technologist" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f468-1f4bb.png"><img class="emoji" alt="man_technologist" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f468-1f4bb.png"></g-emoji> O que foi desenvolvido:
Este projeto trata-se de um projeto para criação de um ambiente de desenvolvimento de front-end com back-end utilizando o `Docker`,
desenvolvido com intuito de aprimorar as habilidades com o `Docker`.

:warning:Atenção:warning:: A parte do Front-end e do Back-end foi desenvolvido pela Trybe para auxilio dos requisitos, o foco do desenvolvimento aqui foi aprender a utilização do Docker

## Técnologias usadas

Back-end:
> Node.js

Front-end:
> JavaScript, React, HTML, CSS

Softwares:
> Desenvolvido usando: Docker


## Instalando Dependências

###### Instalando o back-end

- Acesse a pasta `./todo-app/back-end`;
- Instalar a aplicação utilizando o comando `npm install`;
- Por padrão, essa aplicação funciona a partir da porta `3001`;

###### Instalando o front-end

- Acesse a pasta `./todo-app/front-end`;
- Instalar a aplicação utilizando o comando `npm install`;
- Esse aplicativo requer, **excepcionalmente**, um arquivo `.env` com as variaveis de ambiente;
- Por padrão, essa aplicação funciona a partir da porta `3000`;
- Essa aplicação pode receber variáveis de ambiente para mudar o acesso do `back-end`:
  - `REACT_APP_API_HOST`: padrão `localhost`;
    - *(Docker)* Aqui você deve indicar o nome do container do `back-end`;
  - `REACT_APP_API_PORT`: padrão `3001`.
    - *(Docker)* Aqui você deve indicar a porta que você definiu internamente no container do `back-end`;
 
## Executando aplicação

* Para rodar o back-end:

  ```
  cd docker/todo-app/back-end && npm start
  ```
* Para rodar o front-end:

  ```
    cd docker/todo-app/front-end && npm start
  ```

## Executando Testes

* Para rodar todos os testes:

  ```
   cd docker/todo-app/front-end && npm test
  ```
