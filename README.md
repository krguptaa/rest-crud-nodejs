This is a very basic example of rest api in Node.js 

## Installation

*for newbies : Clone or download zip to your machine then hit this :

`npm install`

## Steps for generating the package for node Js

1. Create the Folder 

`mkdir foldername`

2. initialize the package using npm

`npm init` 

3. Provide the details like 'package name, version and description etc'

4. package.json will created in folder


## Install the express framework, mysql and body-parser

`npm install express mysql body-parser --save`

## Create the server.js file

## Start the node for running

`node server.js`


## Configuration (database)

`````
host: 'localhost',
user: 'root',
password : 'root',
port : 3306, //port mysql
database:'node'	


## Below is the base url for rest api
`http://localhost:8080/`

You might need to pay attention on this , as we're using REST 

``````
Route			HTTP verb	Desc
/todos			GET			Get	All tasks
/todo			POST		Add new task
/todo/:id		GET			Get a task (for editing)
/todo/:id		PUT			Update a task
/todo/:id		DELETE		Delete a task
