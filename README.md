   <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/logo.svg" height = "150"/>


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
  - Tela Inicial
  <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/1.png" height = "400" width = "400" />

  -  Cadastro
  <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/Screenshot_8.png" height = "500" width = "400" />
  
   - Tela de escolha de profissional(User)
  <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/2.png" height = "500" width = "400" />
  
   - Tela de horários e profissionais e agendamento
   <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/Screenshot_5.png" height = "600" width = "400" />
  
   #### Telas do prestador de serviços :
   
   - Dashboard principal
   <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/Screenshot_9.png" height = "400" width = "400" /> 
   
   - Clientes do dia
   <img src="https://s3.us-east-2.amazonaws.com/gobarber-img/Screenshot_6.png" height = "400" width = "400" /> 
    
    
    
