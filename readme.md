# Welcome to the Anythink Market repo

To start the app use: `./start.sh`, it'll start both the backend and the frontend.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Dependencies

Install Docker and make docker -v and docker-compose -v commands run locally

## Operation

Run docker-compose up from the project root directory to load Anythink's backend and frontend.

Connect to the database: localhost:3000/api/ping

If everything is working properly, you’ll be able to create a new user on localhost:3001/register

