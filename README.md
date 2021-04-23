# Abstract Elastic Stack Observability

Service created to abstract layer of observability between the ELK and the application.

# Content

- [Abstract Elastic Stack Observability](aAbstract-elastic-stack-observability)
- [Content](#content)
    - [Informations](#informations)
    - [Features](#features)
    - [Prerequisites](#prerequisites)
      - [Software](#software)
      - [Environment Variables](#environment-variables)
    - [How to start](#how-to-start)
      - [Docker](#docker)
    - [Testing](#testing)
    - [Technologies](#technologies)
    - [Problems and Solutions](#problems-and-solutions)

### [Informations](#informations)

After application is on, you can view the Kibana in port `5601`.

### [Features](#features)

- [x] Docker Configuration.
- [x] Logstash implementation.
- [x] Elastic Search implementation.
- [x] Kibana implementation.

### [Prerequisites](#prerequisites)

#### Software

Before start you're going to need to install:

- [Docker](https://www.docker.com/)

### [How to start](#how-to-start)

#### Docker Compose


Run on your terminal (you should use **WSL** if you are using Windows) the following commands:

- `docker-compose --build-arg LOG_FILE="{LOG_FILE}"`

In which `LOG_PATH` is the file of the application like `C:\Users\josephdsbr\app\logs\` or `/home/josephdsbr/Projects/ProjectX/logs`.

### [Technologies](#technologies)

- [Docker](https://www.docker.com/)
