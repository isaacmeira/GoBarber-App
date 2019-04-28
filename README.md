

# APP GOBARBER
- App criado no desafio 2 do módulo NodeJs no bootcamp Rocketseat

  O aprendizado foi na base de rotas, como elas funcionam da maneira correta, além de criar padrões de projeto MVC, 
  apredemos sobre o uso do nunjucks para renderizar as views.
  
  Além disso foi criado passo a passo o processo de autenticação e criação de usuário, por meio do uso do Sequelize para BD,
  configurado em uma base de dados PostgresSQL, usando uma máquina virtual Docker para tal.
  
 ### COMO USAR:
  É ALTAMENTE RECOMENDÁVEL O USO DO [YARN](https://yarnpkg.com/pt-BR/) e de algum terminal linux, caso você esteja com windows, você pode usar o terminal do GIT.
 
 
  - Primeiramente você precisará ter o docker instalado em sua máquina : https://www.docker.com/get-started.
  - Crie uma conta no site do docker, e assim que instalado, logue nessa conta.
  - Fazer a instalação do DB, pelo terminal usando `docker run --name database -p 5432:5432 -d -t kartoza/postgis`.
  - Criar uma database com o nome "gonodemodulo2".
  - No projeto usar `yarn install` para instalar todas as dependências do projeto.
  - Além disso, `npx sequelize db:migrate` , para criar a base de dados.
  - Após, executar `yarn start`.
  
  ### SCREENSHOTS:
  
  
