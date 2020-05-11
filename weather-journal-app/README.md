# Weather-Journal App Project

## Overview
This project requires you to create an asynchronous web app that uses Web API and user data to dynamically update the UI. 
And we also learn about async javascript.

## Instructions
Open Termianal
Go to Root of the project and press 
```npm install ``` 
This will require modifying the `server.js` file and the `website/app.js` file. You can see `index.html` for element references, and once you are finished with the project steps, you can use `style.css` to style your application to customized perfection.
Before running the server, obtain an API key from OpenWeatherMap.org.
Once the api key is obtained, delete my .env file and create a .env file in the root of the project and add the following line (inserting the key previously obtained):

```
OWM_APIKEY=your-key-goes-here
example - OWM_APIKEY=7495cd95a6fc985a290011d9d43e5454
```
Go to the Project Root and press = npm install which install everything

## Extras
If you are interested in testing your code as you go, you can use `tests.js` as a template for writing and running some basic tests for your code.
You have to options to start the server, one with nodemon and onther one with node.

Start the server with nodemon
```sh
$ npm run start-dev
```

Start the server with node
```sh
$ npm run start
```