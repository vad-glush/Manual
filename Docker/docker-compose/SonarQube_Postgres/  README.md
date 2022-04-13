Иcпользуется версия:
---
SonarQubube 9.4
Postgress 11.4
Docker Compose 2.4.1
---
docker_sonar.yml - файл Docker Compose
sonar.properties - файл настройки SonarQube расположенный в /var/storage/sonarqube/data/conf/
---
Необходима установки внешнего плагина sonarqube-community-branch-plugin
Версия плагина 1.10.0
Плагин необходимо скачать с https://github.com/mc1arke/sonarqube-community-branch-plugin 
.jar положить в /var/storage/sonarqube/data/extensions/plugins/
Блок # WEB SERVER в файле sonar.properties отвечает за подключение плагина