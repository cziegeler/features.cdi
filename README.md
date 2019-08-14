# features.cdi
An OSGi Feature for CDI

This OSGi Feature can be used to launch an OSGi Framework with the CDI support as defined in the OSGi R7 Enterprise Specifications.

As it contains the CDI Sample application, build that one first:
1. git clone https://github.com/cziegeler/samples.guessinggame.cdi
2. Invoke 'mvn clean install' in that project

Then build and run this project:

1. Build this project with 'mvn clean install'
2. Run the OSGi Framework with 'mvn exec:java'
3. Go to http://localhost:8080/system/console (login: admin/admin) or http://localhost:8080/guessinggame/game

