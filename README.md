# webpack-bundle
A basic modularized web site built with webpack, using SASS and lodash. 

### After git pull, run these commands

    npm install lodash
     
    npm install sass
     
    npm install --save-dev webpack webpack-cli
     
    npm install --save-dev css-loader style-loader sass-loader
    
    npm run build

### directory structure

files to be compiled are in `/src`
* entry file for webpack is `/src/main.js`
* SASS file is `/src/style.scss`

files for the webite are in `/www`
* web site index is `/www/index.html`
* webpack output is `/www/js/bundle.js`

node_modules is in `.gitignore` (of course!)




