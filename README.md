## Usage

To install and use locally:
  1. `npm install`
  2. `npm start` (this starts the server and sets up a gulp livereload process)

To deploy:
  We used Heroku to deploy our application. The existing Procfile will suffice
  but you will need to go through a short process (3 cli entries) documented at
  https://devcenter.heroku.com/articles/cleardb#provisioning-the-add-on to prepare
  a MySQL database.

## Requirements

- Node 0.12.2
- Express 4.12.3
- Angular 1.3.15
- MySQL 2.6.2
- Sequelize 2.0.6

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
```

