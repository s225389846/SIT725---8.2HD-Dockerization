- Basis Setup on How to Run Your Container:

1. Clone the GIT Repository.
2. After cloning the repository, make sure Docker is installed in your system.
3. If Docker is not installed, use the following links to install docker:

- OSX: https://docs.docker.com/desktop/setup/install/mac-install/
- Windows: https://docs.docker.com/desktop/setup/install/windows-install/
- Ubuntu: https://docs.docker.com/engine/install/ubuntu/

4. After installing Docker, in the terminal of the root direcory run to build:

- "docker-compose up --build"

5. After the build is complete, to check if the backend code is running, open the browser and access the port for backend:

- "http://localhost:3000/api/student"
- The output displayed there would be:

{
"name": "Trilochan Adhikari",
"studentId" : "s225389846"
}

6. To check if the frontend is running, open the browser and access the port:

- "http://localhost:8085/"
- The output displayed there would be the login page.

7. To check if the docker container is running:

- Open command promt as administrator
- Enter "docker ps"
- You will get the container details
