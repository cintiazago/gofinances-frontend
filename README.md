<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<p align="center">

<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Alquipo/GoStack12-Desafio-07-GoFinances">

<img alt="Repository size" src="https://img.shields.io/github/repo-size/cintiazago/gofinances-frontend">

<a href="https://github.com/Alquipo/GoStack12-Desafio-07-GoFinances/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/cintiazago/gofinances-frontend?color=blue">
</a>

<img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?color=blue">
</p>

<p align="center">

<a target="_blank" href="https://nodejs.org/">
    <img alt="ReactNative" src="https://img.shields.io/static/v1?color=brightgreen&label=Node&message=JS&?style=plastic&logo=Node.js">
</a>

<a href="https://reactjs.org/">
  <img alt="ReactJS" src="https://img.shields.io/static/v1?color=blue&label=React&message=JS&?style=plastic&logo=React">
</a>

</p>
<h2 align="center">
  Desafio 07: GoFinances Web
</h2>

<p align="center">“Não espere resultados brilhantes se suas metas não forem claras”!</p>

## 🚀 Sobre o desafio

Neste desafio, continuamos a desenvolver a aplicação de gestão de transações GoFinances para praticarmos conceitos de React.js juntamente com Typescript e uplad de arquivos através de formulário.

A aplicação devera se conectar ao backend do [Desafio 06](https://github.com/cintiazago/gostack-desafio06-typeorm-upload), e exibir as transações criadas e permitir a importação de um arquivo CSV para gerar novos registros no banco de dados.


## 🔨 Tecnologias:

- [ReactJs][reactjs]
- [TypeScript][typescript]
- [Polished](https://github.com/styled-components/polished)
- [Styled Components](https://styled-components.com/)
- [Axios][axios]



## 🚀 Como rodar este projeto

Para clonar e executar este aplicativo, você precisará de [Git](https://git-scm.com), [NodeJs][nodejs] Instalado em seu computador.

O projeto é composto por duas aplicações:

1. Back-End ([Link do Repositório](https://github.com/Alquipo/gostack-desafio06-typeorm-upload))
2. Front-End

💡 E preciso efetuar o clone e seguir os passos de instalação do [Repositório da API](https://github.com/cintiazago/gostack-desafio06-typeorm-upload)

💡 O Front-End precisa que o Back-End esteja sendo executado na porta 3333 para funcionar.

### 🌀 Clonando o repositório

```bash
# Clone este repositório
$ git clone https://github.com/cintiazago/gofinances-frontend

# Acesse a pasta do projeto no terminal/cmd
$ cd gofinances-frontend
```

### 🧭 Rodando a aplicação web

```bash
# Instale as dependências
$ yarn

# Execute a Aplicação
$ yarn start

# Execute o teste da Aplicação
$ yarn test

# O servidor inciará na porta:3000 - acesse http://localhost:3000
```

## 🛠 Funcionalidades da aplicação


- **`Listar as transações da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na sua API.

- **`Exibir o balance da sua API`**: Sua página `Dashboard`, você deve exibir o balance que é retornado do seu backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importar arquivos CSV`**: Na sua página `Import`, você deve permitir o envio de um arquivo no formato `csv` para o seu backend, que irá fazer a importação das transações para o seu banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).



## 🤔 Como contribuir para o projeto

- Faça um **fork** do projeto;
- Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
- Salve as alterações e crie uma mensagem de commit contando o que você fez:`git commit -m "feature: My new feature"`
- Envie as suas alterações: `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)

## 📝 Licença

Este projeto esta sobe a licença MIT. Veja a [LICENÇA][license] para saber mais.

Feito com ❤️ por Cintia Zago 👋🏽 [Entre em contato!](https://www.linkedin.com/in/cintiazago/)

[nodejs]: https://nodejs.org/
[express]: https://expressjs.com/
[uuidv4]: https://www.npmjs.com/package/uuidv4
[nodemon]: https://www.npmjs.com/package/nodemon
[rs]: https://rocketseat.com.br
[license]: https://opensource.org/licenses/MIT
[Postgres]: https://www.postgresql.org/
[Multer]: https://www.npmjs.com/package/multer
[reactjs]: https://reactjs.org/
[axios]: https://www.npmjs.com/package/axios
[babel]: https://babeljs.io/
[webpack]: https://webpack.js.org/
[rs]: https://rocketseat.com.br
[license]: https://opensource.org/licenses/MIT
[typescript]: https://www.typescriptlang.org/
