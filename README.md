# Projeto API Sequelize

## API NodeJs utilizando Sequelize com banco de Dados MySQL

### Comandos

- npm init -y
- npm install express
- npm install body-parser
- npm install --save-dev nodemon
- npm install --save pg pg-hstore
- npm install --save mysql2
- npm install sequelize sequelize-cli path
- npx sequelize-cli init (Cria os arquivos base do projeto)
- npm run start
- npx sequelize-cli model:create --name Pessoas --attributes nome:string,ativo:boolean (Cria o modelo com seus atributos)
- npx sequelize-cli db:migrate (Criar as tabelas no banco)
- npx sequelize-cli seed:generate --name demo-pessoa (Cria o arquivo seed)
- npx sequelize-cli db:seed:all (Roda os seeds criados)