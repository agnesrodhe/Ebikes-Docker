# Ebikes-Docker vteam#02
A repository containing a docker-compose file to start the system.

An .env file is required to start the system.

To start the system run "docker-compose up -d".
To only start the server run "docker-compose up -d server".

To access the app you need to have the expo app installed on your phone.
You can start the app by scanning the QR code in the web client or paste 
"exp://r6-rq4.anonymous.19000.exp.direct:80" in your phone's browser.

The webclient can be accessed at localhost:3000.

The server can be accessed at localhost:3002.

To shut down all containers run "docker-compose down".