#express
* a web framework that is fast, unopinionated and minimalist
* more polished toolbelt than node's http module
* don't always want to use
* accomplishes specific set of goals
	* good at serving html and json

##express-generator
`npm install express-generator -g`
global install! 

`$ express awesomeTea --ejs`

generates this:

create : awesomeTea2

create : awesomeTea2/package.json

create : awesomeTea2/app.js

create : awesomeTea2/public

create : awesomeTea2/public/javascripts

create : awesomeTea2/routes

create : awesomeTea2/routes/index.js

create : awesomeTea2/routes/users.js

create : awesomeTea2/public/stylesheets

create : awesomeTea2/public/stylesheets/style.css

create : awesomeTea2/public/images

create : awesomeTea2/views

create : awesomeTea2/views/index.ejs

create : awesomeTea2/views/error.ejs

create : awesomeTea2/bin

create : awesomeTea2/bin/www


install dependencies:

   $ cd awesomeTea2 && npm install

run the app:

   $ DEBUG=awesomeTea2:* npm start