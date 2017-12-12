NodeJS

Getting started with node js

Creating Rest service using Node js

Rest(Representational State Transfer) Which means server not storing information about the request or about the client.

Part 1

1) First node need to be install in the machine

   https://nodejs.org/en/

2) Second create a project with

   npm init.

   I had given my project name bookapi. It will create package.json which contain project related info like name, version        description.

3) Third I had install express. It is web framework for nodejs

   npm install express --save

   check package.json it shows under dev dependences. check app.js file for rounting, listening port.

   Run node app.js and hit localhost://3000 in browser.

4) Now added gulp task runner, in order to detect any change to js file, would get reflect in the bowser requesting to the        port. It will help in development and testing purpose.

   Install gulp

   npm install gulp --save

   npm install gulp -g

   npm install gulp-nodemon --save

   check gulp file how to add task which handle any changes in the js file in project and restart the server. It also ignore      the file which will we provide in the task.
