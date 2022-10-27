# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Installing Docker:

Follow the link to get to the Docker documentation https://docs.docker.com/get-docker/ and how to install it for your OS.

After the installation is complete you can check that everything is OK using ```docker -v``` and ```docker-compose -v```.

### Starting the docker instance:

From the project directory run: ```docker-compose up```. After fetching and unpacking all the necessary files go to your browser and load http://localhost:3000/api/ping

If you're able to see ```{"msg":"Pong! Seems like Everythink is working, great job!"}``` it means the app is now running!

Once it is set up go to ```http://localhost:3001/register to register```  to set up a new user.
