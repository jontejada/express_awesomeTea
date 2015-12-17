#express
* a web framework that is fast, unopinionated and minimalist
* more polished toolbelt than node's http module
* don't always want to use
* accomplishes specific set of goals
	* good at serving html and json

##express-generator
`npm install express-generator -g`
global install! 

`$ express awesomeTea`

generates this:
   create : awesomeTea
   create : awesomeTea/package.json
   create : awesomeTea/app.js
   create : awesomeTea/public
   create : awesomeTea/public/images
   create : awesomeTea/public/javascripts
   create : awesomeTea/public/stylesheets
   create : awesomeTea/public/stylesheets/style.css
   create : awesomeTea/routes
   create : awesomeTea/routes/index.js
   create : awesomeTea/routes/users.js
   create : awesomeTea/views
   create : awesomeTea/views/index.jade
   create : awesomeTea/views/layout.jade
   create : awesomeTea/views/error.jade
   create : awesomeTea/bin
   create : awesomeTea/bin/www

   install dependencies:
     $ cd awesomeTea && npm install

   run the app:
     $ DEBUG=awesomeTea:* npm start

