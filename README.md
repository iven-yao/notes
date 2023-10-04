# notes
random notes

- npx:
  
  NPX stands for Node Package eXecute. It is simply an NPM package runner. It allows developers to execute any Javascript Package available on the NPM registry without even installing it.
  for example:
  ```
  $npx knex migrate:latest
  $npx knex seed:run
  ```
  there's no need to install knex cli through ```npm i -g knex``` for using it.

- knex.js:

  knex.js is a sql query builder library that could accomodate for various database. with migrations to create/drop tables and seeds to inserts entries.
  for more info: [knex](https://knexjs.org/) 
