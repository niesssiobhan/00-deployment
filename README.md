![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## 00-Deployment

### Author: Siobhan Niess

### Links and Resources
[![Build Status](https://www.travis-ci.com/niesssiobhan/00-deployment.svg?branch=master)](https://www.travis-ci.com/niesssiobhan/00-deployment)

* [repo](https://github.com/niesssiobhan/seattle-javascript-401d28/tree/master/00-deployment)
* [travis](https://www.travis-ci.com/niesssiobhan/00-deployment)
* [server](https://niess-00-lab.herokuapp.com/)

### Modules
#### `pol.js`
##### Exported Values and Methods
* `isAlive()`
* Returns true or false
  *false if the parameter is sent

### Setup
#### `.env` requirements
* `PORT` - Defined in the ENV
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`
* Endpoint: `/`
* Returns `true`

#### Tests
* npm test (Runs unit tests)
* npm run lint (Runs linter tests)

#### UML
Link to an image of the UML for your application and response to events