ReqRes
======

ReqRes is a bare-bones ExpressJS application.

[Docs & Demos ⇒](http://reqres.in)

## Installation

* Clone repo
* Make sure Node.js is installed on your machine
* `npm install`
* `node app.js` or use [Nodemon](https://github.com/remy/nodemon)

## Tour

* [app.js](https://github.com/interviewstreet/reqres/blob/master/app.js) - this is where we create the Express app and define all of our routes
* [index.js](https://github.com/interviewstreet/reqres/blob/master/routes/index.js) - this is the main file for the callback routes
* [config.json](https://github.com/interviewstreet/reqres/blob/master/config.json) - this houses the pagination details & fake session token
* [resources_config.json](https://github.com/interviewstreet/reqres/blob/master/resources_config.json) - this houses the configurations specific to a particular resource
* [resources/*.json](https://github.com/interviewstreet/reqres/blob/master/resources) - this houses the individual resource data JSON files. The name of the file should be the name of the resource and the file should contain an array of items of that resource. Example: [resources/movies.json](https://github.com/interviewstreet/reqres/blob/master/resources/movies.json)
* [compile_data.js](https://github.com/interviewstreet/reqres/blob/master/compile_data.js) - run this using `node compile_data.js` to generate the final data-set file [data.json](https://github.com/interviewstreet/reqres/blob/master/data.json).
* [data.json](https://github.com/interviewstreet/reqres/blob/master/data.json) - this is the final data-set file. It is generated by joining all the individual resource JSON files.
