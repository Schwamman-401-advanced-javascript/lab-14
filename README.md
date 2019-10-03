# lab-14

## LAB: Access Control

### Author: Jonathon Schwamman

### Links and Resources
* [submission PR](https://github.com/Schwamman-401-advanced-javascript/lab-14/pull/1)
* [travis](https://www.travis-ci.com/Schwamman-401-advanced-javascript/lab-14)


#### Documentation


### Modules

### Setup
#### `.env` requirements
* `PORT` - Port Number
* `MONGODB_URI` - URL to the running mongo instance/db
* `SECRET` - string to be used for JSON web token

#### Running the app
* `npm start`
* Endpoint: `/hidden-stuff`
  * Requires 'read' capability, only allowed by admins, editors, and users - if not logged in denies access
* Endpoint: `/create-stuff`
  * Requires 'create' capability, only allowed by admins and editors
* Endpoint: `/delete-stuff`
  * Requires 'delete' capability, only allowed by admins
  
#### Tests
* How do you run tests?
* What assertions were made?
* What assertions need to be / should be made?
