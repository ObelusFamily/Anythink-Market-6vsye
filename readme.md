# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To setup your environment, you will need first need to setup [Docker]() with [Docker Compose]().
To install it, follow the official docker installation [guide]().

To verify that everything is ready, run the following commands on your terminal:

```sh
docker -v
docker-compose -v
```

If everything is ready, then you can spin up your environment by running:

```sh
docker-compose up
```

If everything went well, you should have a frontend, backend and database running, and you should
be able to connect to `http://localhost:3000/api/ping`.
