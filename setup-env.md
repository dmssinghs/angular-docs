# Angular DEV env dependency tools installation
1. install node
2. create .npmrc file - if you are using private npm package repo
3. install yarn - in your usre's root folder
   1. npm install --global yarn
   2. add yarn's bin folder in windows environment variable "path" - "c:\users\<userid>\AppData\Roaming\npm\node_modules\yarn\bin"
   3. restart command prompt
   4. restart Visual Studio Code
4. environment.ts - change the actual value
5. yarn install
6. yarn start

# angular.json
"scripts": {
    "ng": "ng",
    "start": "set NODE_OPTIONS=--openssl-legacy-provider && ng serve",
    "sonar": "sonar-scanner"
