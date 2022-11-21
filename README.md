# Ebikes-Docker vteam#02
A repository containing a docker-compose file to start the system.

An .env file is required to start the system. Following variables must exist:

ATLAS_USER
ATLAS_PASS
CLIENT_SECRET
CLIENT_ID
NODE_ENV
REACT_APP_GOOGLE_MAPS_API_KEY

To update all containers run "./update_containers.bash" (remember to publish your latest build before running this command).

To start the system run "docker-compose up -d".
To only start the server run "docker-compose up -d server".

The webclient can be accessed at localhost:3000.

The mobile app can be accessed at localhost:3001

The server can be accessed at localhost:3002.

To shut down all containers run "docker-compose down".