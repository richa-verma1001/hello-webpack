## About
A hello webpack very basic tutorial with webpack-dev-server included to act as a web server.

### Prerequisites
+ [Node](https://nodejs.org/en/) and Npm (npm is installed with Node). [Install Instructions](https://nodejs.org/en/download/package-manager/)

### Description
 The project is basic and does not use `webpack.config.js` file. Webpack by default takes the files in the `src` folder and compiles and bundles them together to produce output `dist/main.js` (npm run build). The webpack-dev-server however, does not produce output and save that in the dist/ folder. It instead keeps a cached copy of main.js that is updated and deployed back via webpack on each src edit.

### Run Application
````
npm install
npm run build  OR
npm run production

````
The command below starts the webpack-dev-server and renders index.html in browser
````
npm run start:dev

````

To see result,

```
open index.html
```

Open index.html in your browser. HTTP not required.

### Future Enhancements
+ Add HTTP

### References
+ [Basic beginning webpack OOB](https://www.youtube.com/watch?v=cQakPE9LqKg)
+ [Adding Webpack Dev Server](https://www.youtube.com/watch?v=vci2x0B81P8&list=PLWkguCWKqN9PIG9hxhQiD2PW0DYhk1gue)
