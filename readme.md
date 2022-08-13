# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install [Docker](https://docs.docker.com/get-docker/)
  - Check if Docker is installed correctly by running `docker -v` and `docker-compose -v` in the terminal.
- Run `docker-compose up` from the root directory to load the app frontend and backend.
  - Test if the backend is running at `http://localhost:3000/api/ping`
  - Check the frontend at `http://localhost:3001/register`
