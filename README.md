# JWT-Authentication NodeJs (API)

This is a Nodejs Application that supports Token based Authentication with JWT. The base of the project was taken from bezkoder at [How to Build an Authentication API with JWT Token in Node.js](https://www.section.io/engineering-education/how-to-build-authentication-api-with-jwt-token-in-nodejs/).

## Prerequisites

- [VS Code](https://code.visualstudio.com/)
- [NVM](https://github.com/nvm-sh/nvm)
    - This project was created on Node version v16.11.0
- [MongoDB](https://docs.mongodb.com/)
- [Postman](https://www.postman.com/)

## Database

A new collection 'jwt-project' was created in MongoDB. The name is not relevant since the collection name is updated in .env file.

- Mongo commands MAC Terminal:

    - To check the database is running:

        ```brew services```

    - To create the new collection was

        ```use jwt-project```

    - To check the collection data

        ```db.users.find()```   


## Postman collection

As part of this repository in the resources path at [/resources](https://gitlab.com/JavaJdo/capulus/-/tree/main/src/main/resources) there is a postman collection that can be imported for testing purposes.

Each request shows a set of examples on the different API responses.

![postman](/resources/postman.png)

## Graphic User Interface

This project does not have a particular GUI, instead it is designed to be tested from the API endpoints.