# [ Learning ] - CI/CD Pipeline
This is a CI/CD Pipeline that built by using TeamCity.
The purpose of the CI/CD Pipeline is to publish the .NET application and push to remote server

I utilise the benefit of Docker Compose and to deploy everything with one command.
```
docker-compose -p "teamcity-bundle" -d up
# docker-compose -p "teamcity-bundle" -d up --remove-orphans --force-recreate 
```

It also can be tear down easily by running
```
docker-compose -p "teamcity-bundle" down
```

## Pre-requisite
1. .NET Core installed

## Technology Stack(?)
- TeamCity Agent
- Postgres
- SonarQube
- Docker
