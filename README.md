Setup SonarQube in a Docker Container

Let’s see how we can quickly setup a SonarQube environment using Docker container to run a code analysis for a .NET Core application.

1. Run SonarQube on Docker
2. Install SonarScanner for .NET Core
3. Start the code analysis

# 1. Running SonarQube on Docker
```bash
$ docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube
```