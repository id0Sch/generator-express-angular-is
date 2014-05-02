# Generator express anuglarJS

An Express+Angularjs generator for Yeoman, tailored for my needs.

## Getting started
- Make sure you have [yo](https://github.com/yeoman/yo) installed:
    `npm install -g yo`
- Install the generator **locally**: `npm install generator-express-angular-is`
- Run: `yo express`
- Run: `grunt` to run the local server at `localhost:3000`, the grunt tasks include live reloading for .jade views, css in public/stylesheets and restarting the server for changes to app.js or js in routes/

## MVC apps
I've created a new generator for creating angularJS MVC style apps in express, it's based around [generator-express](https://github.com/petecoop/generator-express). It uses [MongoDB](http://www.mongodb.org/) as it's default database, you will need to have it installed and running to get the default app running.

To get going:

- Make sure you have [yo](https://github.com/yeoman/yo) installed:
    `npm install -g yo`
- Install the generator **locally**: `npm install generator-express-angular-is`
- Ensure that MongoDB is running on your machine, if running elsewhere the connection string can be changed in `config/config.js`
- Run: `yo express-angular-is`
- Run: `grunt` to run the local server - defaults to `localhost:3000` - port can be changed in `config/config.js`. The grunt tasks include live reloading as before.

##Options

currently there are no options to choose from 

##Testing
Tests are written with mocha.
- Install: `npm install -g mocha`
- Run: `mocha`

##Contributing
Contributors are welcome, please fork and send pull requests! If you have any ideas on how to make this project better then please submit an issue.

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License)
