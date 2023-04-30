# Sinau ReactJS for CICD Apps Example
Just try to create an example apps for CICD example.

## Build

* `docker build -t hello-world-react .` to build the Docker image
* `docker run -p 8080:80 hello-world-react` to fire up the container

Visit `http://localhost:8080`, or any port you set it to to view the application.

## Run the development server

You can also run the application on the default React development server by simply running `npm start` in the project's root. It'll fire up the application on `http://localhost:3000`.
