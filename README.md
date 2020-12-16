<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Rocketshoes
</h3>

<p align="center">
  <a href="#rocket-sobre-a-rocketshoes">Sobre o Rocketshoes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias-utilizadas">Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-instalação-e-execução">Instalação e execução</a>
</p>

<p align="center">
  Feito com :purple_heart: by <a href="https://github.com/gabriel-fz" target="_blank">gabriel-fz</a>
</p>

## :rocket: Sobre a Rocketshoes

A Rocketshoes é fruto das aulas do bootcamp GoStack da Rocketseat. Ele é um projeto de um ecommerce de tênis no qual você pode adicionar vários produtos ao seu carrinho e também gerenciar os produtos adicionados graças ao Redux.

## :rocket: Tecnologias utilizadas

Para o desenvolvimento da Rocketshoes foram utilizadas as seguintes tecnologias:

- [Node](https://nodejs.org/en/)
- [React](https://reactjs.org/)
- [React-Icons](https://react-icons.netlify.com/#/)
- [Redux](https://redux.js.org/)
- [Styled-Components](https://styled-components.com/)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Json-Server](https://www.npmjs.com/package/json-server)

## :rocket: Instalação e execução

A seguir, estão descritos todos os passos para a instalação e execução

### :memo: Pré-requisitos

- [Node](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/pt-BR/docs/install#debian-stable)
- [Git](https://git-scm.com/downloads) (Opcional)

### :octocat: Clonando o repositório

Abra em sua máquina uma pasta de sua preferência. Em seguida, abra o terminar de sua máquina na respectiva pasta e rode o seguinte comando:

```
$ git clone https://github.com/gabriel-fz/Rocketshoes.git
```

Ou então, baixe este repositório zipado.

### :computer: Instalação e execução do Frontend

Inicialmente na pasta raiz, digite o comando `yarn` para que todas as dependências sejam baixadas.

Após baixar todas as dependências, abra a pasta raiz no prompt de comando e execute o seguinte comando para poder rodar o json-server:

```
json-server server.json -p 3333
```

**Observação:** A porta 3333 do comando acima condiz com a porta 3333 do arquivo `src/services/api.js`, sendo que os mesmos precisam estar utilizando a mesma porta.

Com o json-server rodando, basta então abrir uma outra aba no terminal (ainda na pasta raiz do projeto) e digitar o seguinte comando:

```
yarn start
```

Ao final, será aberto em uma aba do seu navegador a página da Rocketshoes onde é possível interagir adicionando produtos ao carrinho e administrando o carrinho.
