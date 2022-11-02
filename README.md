# ESM Forum

O **ESM Forum** é um sistema de demonstração do livro [Engenharia de Software Moderna](https://engsoftmoderna.info). O objetivo é permitir que os alunos tenham um contato prático com os conceitos estudados no livro. Ou seja:

* Trata-se de um projeto com **objetivo didático** e, por isso, **não temos a intenção de colocá-lo em produção**. 

* Também **não temos a intenção de implementar um sistema completo**, com todas as funcionalidades de um sistema real.

O sistema é um fórum simples de perguntas e respostas

## Linguagens e Bibliotecas

O ESM Forum é implementado em JavaScript, usando:

* No frontend:
  * Bootstrap, um framework para construção de interfaces Web usando HTML e CSS.

* No backend:
  * Node.js, um sistema que permite a execução de programas JavaScript fora de browsers.
  * Express, uma biblioteca para construção de aplicações Web em Node.js.
  * SQLite, um banco de dados relacional simples e implementado na forma de uma biblioteca.
  
## Instalação

Primeiro, clone o repositório:

``` git clone https://github.com/mtov/esmforum.git```

Em seguida, instale a versão mais recente do Node.js. Mais informações [aqui](https://nodejs.org/en/download).

Instale também as seguintes dependências:

```
sudo apt update
sudo apt install sqlite3 
npm install better-sqlite3
```

## Execução

Na primeira vez que for executar o sistema, é importante antes criar o banco de dados. Para isso, faça:

```
cd bd
./criar_bd.sh
```
Para executar o servidor, digite:

``` node server.js```

Para acessar o sistema, abre a seguinte URL no browser:

``` http://localhost:3000 ```

