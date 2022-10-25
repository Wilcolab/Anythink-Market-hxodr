# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When impl`ementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup - Setting up your environment 

- Download and install docker.
- Verify docker installation in your terminal by running: `docker -v` then `docker-compose -v`.
- Run `docker-compose u` in your terminal.
- go to http://localhost:3000/api/ping to check if backend is working.
- check the frontend and make sure it’s connected to the backend: If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register 