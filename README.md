# React_Intro

## Intro

Make sure you have installed git, Node.js and yarn.

node.js - https://nodejs.org/en/download/

git - https://git-scm.com/download/win

Run this for the first project ever. Good intro clone, cd into the project, download yarn, and use it.

git clone https://github.com/figment-networks/learn-web3-dapp.git

cd learn-web3-dapp

yarn

yarn dev


## React app

Open to a completely blank project 

The first thing we want to do is create our React application

*need to be in a folder that has no capital letters or spaces in it

1. Open a Command Prompt (cmd)

2. Make sure you have node installed by typing the following:
    
    node -v

    If you see a version that means you have node installed. 
    Else you'll need to type:
    
    npm install node

3. Now that we have node js running we'll want to create our react application

    npx create-react-app folder_name

4. Once everything is done downloading that folder will be populated with a bunch of files 
and a bunch of commands we can use

    cd folder_name
    npm start, npm run build, npm test, npm run eject, etc. 

5. sometimes I run into an error with one of my dependecies - try one of the following:

    npm install --legacy-peer-deps 

    npm install --force

    npm audit fix --force
