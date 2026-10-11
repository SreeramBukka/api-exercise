## Glide User API Exercise

#### Overview

Welcome to the Glide coding challenge for the software engineer position. This challenge is designed to understand how you approach problem-solving and develop solutions that you would be confident to deploy in a production environment.

#### Objective

Within this repository, you will find a test file in the root directory, containing integration tests for the desired behavior of an API. Additionally, we have provided the data that the API should interact with in [users.json](users.json). Your task is to write the API implementation so that the integration tests pass.

The tests target `http://localhost:3000`. Please ensure that your implementation works against this URL. We have set up a basic [server.js](server.js) file to get you started. However, you're free to choose any technology and implementation approach – if you prefer to use Go, Ruby, etc., please feel free to do so. This task is meant to be technology agnostic. One recommendation though, due to time constraints we would suggest using the file system as your datastore. You don't want to use all your time getting a datastore like postgres running.

### Evaluation

Our aim with this task is to understand how you think through problems and the steps you take, rather than just completing the task within the allotted time. Focus on how you would approach the implementation to make it production-ready, rather than rushing to pass the integration tests.

### Setup

Clone the repo into your local development environment and get the app running:

```js
npm install
npm run test
```

If you want to use the existing Express server, run:

```js
npm run server
```

This command starts the Express server configured in server.js, serving the API on `http://localhost:3000`. Finally run the test command again to validate that the server is working:

```js
npm run test
```



### Queries

If you have any opinions, thoughts, or need clarification on any aspect of the challenge, please do not hesitate to discuss these with us during the interview. We value open communication and are keen to understand your perspective and reasoning.

This repository has a starter server, a users.json data file, and integration tests that define the expected API behaviour. Your task is to implement the missing functionality and make the tests pass. It recommends using the filesystem as the datastore, so you don't need PostgreSQL


Task 1 — Implement the user API
Read the existing tests and users.json. Implement the API behaviour specified by the tests using the existing server and JSON data.
Your objective is to get all the tests passing without breaking the existing structure.

02

Add search
Add a way to search users by name or email, ignoring letter case. Return an empty result when no users match.



03

Add pagination
Support page and limit parameters. Return the requested subset and useful pagination metadata.


Good luck, and we're excited to see you get creative!
