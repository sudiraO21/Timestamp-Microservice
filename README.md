
# [Timestamp Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice)

This is my project of the [Timestamp Microservice challenge](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice) for the freeCodeCamp API and Microservice certification.

[Live Demo](https://timestamp-microsevice.sudirao21.repl.co/)

## Endpoints:

Endpoints | Description
----------|-------------
GET `/api/timestamp` | Return a date object with unix timestamp and UTC timestamp of the current timestamp
GET `/api/timestamp/{dateParam}` | Return a date object of the informed timestamp (unix or UTC ISO-8601)

# Installation

```bash
# Install dependencies
$ npm install

# Run the app
$ npm start
```
Access it at localhost:3000

#### Example usage:
* https://timestamp-microservice.sudirao21.repl.co/api/timestamp
* https://timestamp-microservice.sudirao21.repl.co/api/timestamp/2015-12-25
* https://timestamp-microservice.sudirao21.repl.co/api/timestamp/1451001600000

#### Example response:
```json
{
  "unix":1451001600000, 
  "utc":"Fri, 25 Dec 2015 00:00:00 GMT"
}
```
