# API Nodejs utilizando Mysql, Express, Nodemon

## Rodando o Projeto

Obs: Verificar se possui o npm e nodejs
node -v
npm -v 
no terminal

1) fazer download do projeto
2) ao baixar o projeto ir no terminal e fazer :
npm install 
3) para rodar o projeto: npm run dev 
4) Verificar login e senha do seu banco de dados utilizado, no meu caso utilizei o mysql

## Arquivo e pastas do projeto 

 - `/repositories` - é responsabel pela persistencia dados, porem relacionado ao banco de dados
 - `/controllers` - é responsável por gerenciar as solicitações de entrada e saída da aplicação 
 - `/database` - arquivo reponsavel configuracao do banco dados 
- `routes.js`  - arquivo responsavel pela rotas
- `server.js` - arquivo responsavel pela configuracao da porta da aplicacao
- `app.js` -  arquivo responsável por configuracao a aplicacao e definir as principais configurações, middleware e inicializar as rotas.
- `.gitignore` - arquivo que serao ignorados pelo git ao subir a aplicacao
- `package.json` - arquivo responsavel pelo gerenciamento de dependencias, scripts, metadados do projeto,
- configuracao do ambiente de desenvolvimento, inicializacao do projeto, scripts de publicacao e build

## Dependências
- `Mysql` - Banco de dados
- `Express` - é um framework web para Node.js que simplifica o desenvolvimento de aplicativos web e APIs.
- `Nodemon` - é uma ferramenta de desenvolvimento que monitora alterações no código-fonte e reinicia automaticamente o servidor Node.js 


## Padrao Singleton 
O padrão Singleton é um padrão de criação que se concentra na criação de uma única instância de uma classe e no fornecimento de um ponto global de acesso a essa instância.

## Insomnia
- (Foi utlizando o aplicativo insomnia para efetuar os testes na aplicacao) 

[TelasDoProjeto] - (https://imgur.com/a/Ntq8LnI)



