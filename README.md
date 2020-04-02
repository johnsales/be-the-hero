App created in a course practice from omnistack 11 using React

- React for frotend
- Node for backend
- React Native for mobile

some commands used during the development

Install Node + NPM
Install VisualCode
Install Nodemon (restart node automatically)
Install Insomnia (similar postman)


//creating the backend node
npm init -y
npm install express

//to execute
node + js file OR npm + somescript you declared in package.json

//create react app
npx create-react-app myapp

//to execute
npm start

//install querybuilder and your database
npm install knex
npm install sqllite3

//databse structure
npm knex migrate:make mymigration (in migration file, create the tables, columns and relationships)

//execute all scripts from migration
npx knex migrate:lastest

npx knex migrate:status

//segurança do backend
npm install cors

//icons
npm install react-icons

//routes
npm install react-router-dom

//client hppt frontend
npm install axios

//mobile ('EXPO': making universal native apps for Android, iOS, and the web with JavaScript and React)
npm install -g expo-cli

//creating app
expo init mobile

//to execute mobile
npm start

//React Navigation
npm install @react-navigation/native
--Installing dependencies into an expo managed project
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
-- navitation chosen was stack (by buttons)
npm install @react-navigation/stack

//constantes
expo install expo-constants

//email
expo install expo-mail-composer

//client hppt mobile
npm install axios

//intl currency etc.. for mobile
npm install intl

#generating apk and ipa from expo
Youtube: 'Gerando APK e IPA com React Native & Expo | Code/Drops #15'

#advanced features

//validation
npm install celebrate

//install and execute test
npm install jest -D/ npx jest --init

//to recognize the enviromnent
npm install cross-env

//test request http and validate
npm install supertest -D

#deploy backend
[simple] (heroku) just for test - Youtube: 'Deploy de aplicação NodeJS e React no Heroku'
[medium] (digital ocean) with users - Youtube: 'deploy de apps Node.js' Masterclass #03
[big]  (aws, azure and google cloud platform)

#deploy frontend
[simple and medium] - netlify (sign up and connect with github and it's gone, the platform understand the language and deploy magicly)

#future studies
- padrões de código ESLint, Prettier
- Autenticação JWT
- Styled Components
