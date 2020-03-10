# NodeMailDemo

## NodeMailer Doc: https://nodemailer.com/about/

1. Create a Github Repo

2. npm init
    - entry point: app.js
    - author: Your Name

3. Install Dependencies
    - express
    - body-parser
    - express-handlebars
    - nodemailer
        * npm install express body-parser express-handlebars nodemailer

4. Create app.js file

5. npm install -g nodemon

6. Require each of your dependencies in app.js 
    - EX: const express = require('express');

7. Initialize app variables
    - const app = express();
    - GET route for the landing page or '/'

8. In your terminal run: 
    - node app.js

9. Setup View Engine
    - app.engine('handlebars', exphbs());
    - app.set('view engine', 'handlebars');

10. Body Parser MiddleWare 

11. Setup Public Folder