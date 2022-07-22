# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Ensure you have docker and docker-compose installed on your machine. Instructions are available (here)[https://docs.docker.com/get-docker/]

Run the following:

```bash
docker-compose up
```

Checking the backend works you can hit the following endpoint: [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

Next sign up for an user account on the frontend at: [http://localhost:3001/register](http://localhost:3001/register)
