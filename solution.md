# How to build and run the PurpleCow
To build and run PurpleCow, there are tow methods available to achieve this. You can either run the service using node or using Docker.

## Run using node
To run this project running node, simply enter the command `node index.js 3000` in the root directory of this app. The number `3000` is in the command position to specify which port you would like the service to run on. If you would like to run the service on any other port, simply swap out the number `3000` for any other port you would like to use. Once the service is running locally, go to your browser and go to `localhost:3000` to view the services main page.

## Run using Docker
To run the service using Docker, make sure youa re in the projects root directory and run `docker build . -t PurpleCow`. Once the contianre is done building, run `docker run PurpleCow`  By default, the service will run on port `3000`, so once the service is running, enter the command `ifconfig`, find the IP address of the service, navigate to your browser, and go to `<ip-address>:3000`.

### Modules used in this project
* `express.js`: I decided to use express becasue I built my personal site with express, which just so happened to be my first node project I ever created, so express has a special place in my heart.
* `pug`: I used pug because the syntax is much easier to navigate and handle compared to standard HTML. I also like the indentation syntax, which is similar to Python, the language I am most ocmfortable using.