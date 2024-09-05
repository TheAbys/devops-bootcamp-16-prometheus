#### This project is for the Devops bootcamp module "Monitoring"

##### Metrics
The project exposes metrics on /metrics endpoint

To run the nodejs application:

    npm install 
    node app/server.js

To build the project:

    docker build -t mueller/demo-app:nodeapp .
    docker push mueller/demo-app:nodeapp