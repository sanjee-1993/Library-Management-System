# Library-Management-System
Library management systems also involve maintaining the database for entering new books and recording books that have been borrowed with their respective due dates.

# 19 jul 2020 

Create a package.json file§

To create a package.json file, on the command line, in the root directory of your Node.js module, run
 `npm init`:

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.



Installing Express

Firstly, install the Express framework globally using NPM so that it can be used to create a web application using node terminal.

`npm install express --save`


The above command saves the installation locally in the node_modules directory and creates a directory express inside node_modules. You should install the following important modules along with express −

body-parser − This is a node.js middleware for handling JSON, Raw, Text and URL encoded form data.

cookie-parser − Parse Cookie header and populate req.cookies with an object keyed by the cookie names.

multer − This is a node.js middleware for handling multipart/form-data.

1) `npm install body-parser --save`
2) `npm install cookie-parser --save`
3) `npm install multer --save`


*https://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm



Request & Response
Express application uses a callback function whose parameters are request and response objects.

`
	app.get('/', function (req, res) {
	   res.send('Hello World');
	})
`


Request Object − The request object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on.

Response Object − The response object represents the HTTP response that an Express app sends when it gets an HTTP request.

You can print req and res objects which provide a lot of information related to HTTP request and response including cookies, sessions, URL, etc.