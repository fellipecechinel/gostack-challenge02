# gostack-challenge02
GoStack - Challenge 02 - Initial lessons with NodeJs

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Install Node and Yarn

### Installing
Execute this command to download the dependences
```
yarn
```
After finished execute the command to start the aplication
```
yarn dev
```

## REST API
### List Repositories
```
GET - http://localhost:3333/repositories
return: 
[{
  id,
  url,
  title,
  techs,
  likes
}]
```

### Create Repositorie
```
POST - http://localhost:3333/repositories - body: { id, url, title, techs }
```

### Update Repositorie
```
PUT - http://localhost:3333/repositories/:id - body: { url, title, techs }
```

### Delete Repositorie
```
DELETE - http://localhost:3333/repositories/:id
```

### Add Like to Repositorie
```
POST - http://localhost:3333/repositories/:id/like
```

## Running the tests
Execute this command to running the tests
```
yarn test
```

## Built With

* [NodeJs](https://nodejs.org/) - JavaScript runtime built on Chrome's V8 JavaScript engine.
* [Express](https://expressjs.com/) - Web framework for Node.js
* [Nodemon](https://nodemon.io/) - Monitor for any changes in your source and automatically restart your server

## Acknowledgments

* Everyone at RocketSeat with their incredable lessons :purple_heart:
