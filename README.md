# sonarqube
docker-compose up

# sonar-scanner
Donwload: 
> https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner


> wget https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-3.2.0.1227-linux.zip

unzip sonar-scanner-cli-3.2.0.1227-linux.zip

mv sonar-scanner-3.2.0.1227-linux/ /opt
ln -s /opt/sonar-scanner-3.2.0.1227-linux/ /opt/sonar-scaner

ln -s /opt/sonar-scanner/bin/sonar-scanner /usr/bin/sonar-scanner


# use
-> http://localhost:9000
