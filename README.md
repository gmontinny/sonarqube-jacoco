## Pre-requisites
* JDK 11+
* Docker

## Running

#### Rodando SonarQube
`./gradlew composeUp`

Isso executará o SonarQube em [locahost:9000](http://localhost:9000).
O login padrão é *admin/admin*, então você precisará definir uma nova senha.

#### Executando uma varredura do SonarQube
Aguarde o SonarQube iniciar e execute:

`./gradlew sonarqube`

## Parando
`./gradlew composeDown`

