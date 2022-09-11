# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
**[Docker](https://www.docker.com)** is needed to use this repository.

1. With docker installed, make sure it is working by issuing the commands `docker -v` and `docker-compose -v`, which should return the versions of docker and docker-compose if successful.

2. To spin up this project run `docker-compose up`, which will download and setup the necessary containers for the frontend and backend.

3. Frontend can be accessed by visiting `http://localhost:3001`, backend can be checked by visiting `http://localhost:3000/api/ping`.
