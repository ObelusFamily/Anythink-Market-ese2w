# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_


## Dev Environment Setup

**[How To Setup Your Local Environment]:** 
You'll need to have WSL and any Sub distro of linux installed on your windows machine first, do this to avoid unnecessary installation problems. 

Next, Docker. You can get the setup @https://docs.docker.com/get-docker/.
when you've gotten docker installed restart your machine. afterwards, install the docker extension on your code editor,and open your git repository.

In Your Terminal run (docker-compose up) and wait for it to compile your project,
then try http://localhost:3000/api/ping to confirm that the container is active .this is your backend interface

after which you can try http://localhost:3001/register to confirm the frontend is active