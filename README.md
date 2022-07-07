# My-Tech-Blog

![License Badge](https://img.shields.io/github/license/jak3ster/My-Tech-Blog) ![Top Language](https://img.shields.io/github/languages/top/jak3ster/My-Tech-Blog)

A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. Site is built completely from scratch and deployed on Heroku and follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Installation

1. Download or clone repository
2. Node.js is required to run the application
3. `npm install` to install the required npm packages

## Usage

* To start using the application, use mySQL Workbench to setup the database and seed using files:

      * [scheme.sql](./db/schema.sql)
      * [seed.sql](./seeds/seed.sql)

* The application is invoked by running `node server.js` in the command line  
* Open a browser and navigate to <http://localhost:3001/>
* Shows the homepage to interact with the blog site.

## Demo and Links

* [Heroku](https://jak3ster-techblog.herokuapp.com/)
* [Github](https://github.com/jak3ster/My-Tech-Blog)

## Features

* JavaScript
* Node.js
* MySQL
* npm packages
  * bcrypt
  * connect-session-sequelize
  * dotenv
  * express
  * express-handlebars
  * express-session
  * mysql2
  * sequelize

## License

  Licensed under the [MIT](LICENSE) license.
