## <a href="https://stackblitz.com">Online IDE</a>

# GIT - <a href="https://git-scm.com/">documentation</a>

## Start
#### git config --global user.name "loginGithub" //init loginGithub
#### git config --global user.email "your@email" //init email

## Init project
#### git clone linksGithubRepository //copy remote repository
#### git init //local repository => git repository

## Branch 
#### git branch  //View all branch
#### git checkout nameBranch //Go to branch
#### git checkout -b nameBranch //Create a new branch and go to it
 
## Commit and push 
#### git add . (or -A) //Indexing change in local folder
#### git commit -m "name: commit"  // Create commit end fix change
#### git push origin master  //Push on the remote repository in the branch master

## Pull 
#### git pull origin master (or -f if errors)  //Return is remote repository in the local folders (fix change)
#### git fetch origin master //Return is remote repository in the local folders (no fix change)

# Yarn install command

## Yarn - <a href="https://yarnpkg.com/">documentation</a>
#### npm install --global yarn //install yarn
#### yarn --version //check install yarn
#### yarn init --yes //init project yarn and create package.json

## Express - <a href="https://expressjs.com/ru/">documentation</a>
#### yarn add express //install express

## Nodemon - <a href="https://nodemon.io/">documentation</a>
#### yarn add nodemon --dev  //Install nodemon
#### yarn nodemon --inspect index.js //Start nodemon
 
## TypeScript - <a href="https://www.typescriptlang.org/">documentation</a>
#### yarn add typescript ts-node @types/node @types/express --dev //Install TypeScript
#### yarn tsc --init  //Init TypeScript project and create tsconfig.json
#### yarn tsc -w //Start watcher mode

## Jest and Supertest - <a href="https://jestjs.io/ru/">documentation</a>
#### yarn add jest ts-jest @types/jest supertest @types/supertest  //Install Jest and Supertest архитектура приложения
#### yarn ts-jest config:init //Init Jest and create jest.config.js
#### yarn test - Start test

## Express-validator - <a href="https://express-validator.github.io/docs/">documentation</a>
#### npm install --save express-validator //Install Express-validator

## Mongo DB
### yarn add mongodb
### npm install -D @types/node

## dotenv
### npm i dotenv

# Application architecture

## folder .
#### _tests_ //test files to B2B
#### .gitignore //not pushed to remote directory
#### *.json //configuration files

## folder src
#### controllers //endpoints request and response
#### middleware //middlewares validation/autentification
#### models //interface and type variables
#### routes //routes server, index.ts, request and response
#### services //algoritms and work to data layers
