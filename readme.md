# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Testing Docker in Project Root

First step is to verify that Docker is installed and ready by running `docker -v` and `docker-compose -v` in your terminal. If they return a version number, it is correctly installed.

### Loading the Docker container

Run `docker-compose up` from the project root directory to load Anythink's backend and frontend. After the Docker container has finished setup and is running, test to see if everything is working by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

### Creating a new user

Once the backend has been verified as working correctly, you'll be able to create a new user on [http://localhost:3001/register](http://localhost:3001/register).