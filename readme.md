# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps for setting up the local environment
Following are the steps to setup a local development environment

Step 1 :
Install Docker from this link (https://docs.docker.com/get-docker/)
Steps to install Docker are very well documented on the official Dockers docs.

YouTube video link for reference (https://www.youtube.com/watch?v=Vplj9b0L_1Y)
First download Docker desktop
Then insatll Docker engine 
Thne install Docker desktop

Step 2:
Verify that docker is installed and working properly by running these commands in terminal
docker -v 
docker-compose -v

Step 3:
run (docker-compose up) from the project root directory to load Anythink's backend and frontend.

If Docker is working correctly, the backend should be running and able to connect to your local database.

Let's test this by pointing your browser to http://localhost:3000/api/ping
