## thinApp

The task here was to create a lightweight app, the thinnest possible, that responded to http requests using Express.  I used the following process and technologies:
1. Set up new npm package:
    * Specify app.js as your entry file
2. Install Express, `npm install express`.
3. Create app.js.
4. In app.js:
    * Create an Express application.
    * Define a GET "/" route.
    * Instruct the app listen on a port 5000.
5. Navigate to root directory of the project, `node app`.
6. In browser or Postman, make a get request to localhost:5000.
7. The response should be a json object {msg: "hello world"}.
