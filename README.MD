# Run command
```npm init```
# Run command
```
npm install webpack webpack-cli webpack-dev-server --save-dev
npm install babel-loader babel-core babel-preset-env babel-preset-react --save-dev
npm install html-webpack-plugin copy-webpack-plugin --save-dev
npm install style-loader css-loader sass-loader node-sass --save-dev
npm install react react-dom
npm install bootstrap --save
```
# add to package.json
```
"scripts": {
    "start": "webpack-dev-server --open --hot --progress --colors --inline",
    "build": "webpack -p --progress"
},
```
