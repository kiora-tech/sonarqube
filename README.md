# Sonarqube
## Dependencies
- Docker
- Docker-compose
- A ngrok account


## Installation
1. Run the following command to start the installation:
```sh
docker-compose up -d
```
2. If you have trouble with memory use this command 

```sh
sudo sysctl -w vm.max_map_count=262144
```


## usage
  Go to https://dashboard.ngrok.com/tunnels/agents to konw your address, and use the  Sonarqube documentation


- sonar-project.properties

```
sonar.projectKey=YOUR_PROJECT_KEY
```

if code coverage
```
sonar.php.coverage.reportPaths=coverage.xml
```