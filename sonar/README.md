# Sonar

Create a env file which looks like this, configure a tunnel in cloudflared with the domain `http://sonarqube:9000` and also create the proper directories. If you have this, create a .env file in the same directory like this:

```shell
TUNNEL_TOKEN=<your token>
SONARQUBE_CONF=/home/joel/config/sonar/conf
SONARQUBE_DATA=/home/joel/config/sonar/data
SONARQUBE_EXTENSIONS=/home/joel/config/sonar/extensions
SONARQUBE_LOGS=/home/joel/config/sonar/logs
SONARQUBE_TEMP=/home/joel/config/sonar/temp
SONAR_DB=/home/joel/config/sonar/db
SONAR_DB_DATA=/home/joel/config/sonar/dbdata
```
