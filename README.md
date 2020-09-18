Udemy course at https://www.youtube.com/watch?v=SvJFeKg5NLc demonstrating mern using next.js, react.js, node.js and mongodb.

### Server set up
* Create backend and frontend dirs
* cd to backend and initialize backend - npm init -y
* Install initial dependencies - `npm i express body-parser cookie-parser mongoose morgan nodemon dotenv cors`
* Create server.js
* Add start script to package.json
* Run server - `npm start`

### DB set up
* Install mongodb (if not already installed locally) and start up.
* Set env vars for local and cloud mongo db (ensure mongodb is installed and running
* Connect to db via mongoose and test local and cloud connections

## Processes
* Run through initial set up as per above.
* Create basic route and controller and test.
* Create schema for User model.
* Add  basic route and controller for signup (using the user model) and test api in Postman.

### Signup process
* Install packeage for validation process - `npm install express-validator jsonwebtoken express-jwt formidable lodash slugify string-strip-html`
* Create methods on userSchema to hash and validate password
* Generate unique name using shortid - `npm install shortid`
* Test api response in Postman and check mongodb for new record.







