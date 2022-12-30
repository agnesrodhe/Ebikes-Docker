# WEBIKE Project
This is the main repository for the Webike system. This repository represent the **Docker-compose** to start the quick-use of the system. 
## Cloning and Running the Application in local
Clone the project into local

An .env file is required to start the system.  
Create an .env file in the project folder. The following variables must exist in the .env file with values:
- ATLAS_USER
- ATLAS_PASS
- CLIENT_SECRET
- CLIENT_ID
- NODE_ENV
- JWT_SECRET
- REACT_APP_GOOGLE_MAPS_API_KEY

Go into the project folder and type the following command to update all containers.
```bash
./update_containers.bash
```

To start the system run the following command. 
```bash
docker-compose up -d
```
To only start the server run the following command.
```bash
docker-compose up -d server
```

To shut down all containers run the following command.
```bash
docker-compose down
```

**The WebClient can be accessed at localhost:3000.**

**The WebClient/web application can be accessed at localhost:3001**

**The REST API can be accessed at localhost:3002.**

## Main-repository for the system
### Docker-compose:
Docker-compose repository for quick-use of the system. 
##### Github Url:
https://github.com/agnesrodhe/Ebikes-Docker
## Sub-repositories
### WebClient - Administrator
WebClient for the Webike project for the admin interface.
##### Github Url:
https://github.com/agnesrodhe/EBikes-Web-Client.git
### WebClient/Web application - Customer
Responsive WebClient/web application for customer interface.
##### Github Url:
https://github.com/agnesrodhe/Ebikes-Mobile-Web-App
### Backend
Database and REST API for the Webike system.
##### Github Url:
https://github.com/agnesrodhe/EBikes-Backend
### E-scooter simulation
Electric scooter simulation for the system.
##### Github Url:
https://github.com/agnesrodhe/EBikes-Bike-Intelligence