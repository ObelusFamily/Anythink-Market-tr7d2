# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install Dokcer Desktop from here [Windows](https://docs.docker.com/desktop/install/windows-install) [Linux](https://docs.docker.com/desktop/install/linux-install) [Mac](https://docs.docker.com/desktop/install/mac-install).

2. Confirm Docker installation by running below commands:
```
docker -v
docker-compose -v
```

3. Then run `docker-compose up` or `docker-compose up -d` (To run in detached mode).

4. Wait few minutes to install all the necessary dependencies. When it is done visit this URL `http://localhost:3000/api/ping` to confirm.

5. If everything works properly, you'll be able to create new user from here `http://localhost:3001/register`