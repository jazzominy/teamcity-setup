# A sample Teamcity setup for local system
This is a sample Teamcity setup for local system. It uses the official Teamcity images from JetBrains. The setup is based on the [Teamcity Docker Samples](https://github.com/JetBrains/teamcity-docker-samples) repository.

## Prerequisites
We need the following to be installed on the system:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Setup
- Clone the repository
- Run `docker-compose up -d` to start the containers
- Open `http://localhost:8111` in your browser
- Follow the instructions to setup the server
- Once the server is setup, you can create a project and add a build configuration
- Authorize the unauthorized agent
- Assign the build configuration to the agent

## Notes
- The server data is stored in the `data` directory
- The server logs are stored in the `logs` directory

## References
- [Teamcity Agent Image](https://hub.docker.com/r/jetbrains/teamcity-agent)
- [Teamcity Server Image](https://hub.docker.com/r/jetbrains/teamcity-server)
- [Teamcity Docker Samples](https://github.com/JetBrains/teamcity-docker-samples)