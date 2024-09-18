# Instrucoes

https://medium.com/@denis.verkhovsky/sonarqube-with-docker-compose-complete-tutorial-2aaa8d0771d4


## Rodar o projeto
```
docker-compose up
```

- To run SonarQube we need two service: SonarQube itself and a Database.

- To be able to keep our analysis results we need to setup volumes as well. You might want to setup them in different location though, but for the simplicity we’ll let docker itself to decide, where they would be located on you host machine. It’s needed because by default if Docker container is removed for any reason, the data will be lost as well without volumes.

- OWASP dependency check plugin for SonarQube. This plugin helps to verify that your code doesn’t have a vulnerabilities. The actual binary could be downloaded here.

## Usar a tela
```
http://localhost:9001/
```
Login: admin

Password: admin
