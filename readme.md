# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. To verify you have Docker on your machine in the terminal run `docker -v`and `docker-compose -v`
2. Run `docker-compose up` **from the root directory** of the project files
3. **Test if the backend** is running by **visiting this [link](http://localhost:3000/api/ping) in your browser**
4. Check if the frontend is connected to the backend by **visiting this [link](http://localhost:3001/register) in your browser**
5. **Create a new user** at the same [link](http://localhost:3001/register)
