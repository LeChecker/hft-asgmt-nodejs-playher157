[![Build Status](https://travis-ci.org/hft-stuttgart-ipr/hft-asgmt-nodejs-playher157.svg?branch=master)](https://travis-ci.org/hft-stuttgart-ipr/hft-asgmt-nodejs-playher157)

# hft-asgmt-nodejs

## TODO
  - [X] Install and use the `body-parser` package
  - [X] Install and use the `sqlite3` package
  - [X] Use names for your form fields: `username` for the username and `message` for the textarea
  - [X] bodyParser must support json and should also use the option flag `extended:true`
  - [X] Iterate over all items in your database and show them in your table
  - [X] Refactor the `GET /` route to deliver your index page with data from the database
  - [X] Create a route, for `POST /add-entry` to receive form data

## Hints
 - It is not necessary to store the ID in the Database! `username` and `message` is enough! This is because of the sqlite autoincrement feature, which automatically increases the ID + 1
 - [https://www.npmjs.com/package/body-parser](https://www.npmjs.com/package/body-parser) -> Check examples for how to use bodyParser for json
 
