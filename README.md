# Express Typescript Typeorm Service Boilerplate

This is a boilerplate to set up a node.js API service with express typescript and typeorm running with docker.

## Description

A microservice boilerplate packed with all the goodies node.js ecosystem has to offer:
* express.js as web server
* typescript
* typeorm
* jest for tests
* docker to rule them all :)


## Getting Started

### Dependencies

* Node.js 12
* npm
* Docker

### Installing

* Clone the repo locally
* Run `npm install`

### Executing program

* To run the service use the following commaind:
```dockerfile
docker-compose up -d
```

* To check if the service is running:
```bash
curl http://localhost:3000/
```

## Help

* To see the service logs run from the service root directory:
```dockerfile
docker-compose logs --follow
```
* To run the service tests:
```javascript
npm run test
```
## Authors

[@Aku](https://twitter.com/ozam15)

## Version History

* 1.0.0
    * Initial Release

