# prj01-web

```
git clone https://github.com/thibhen/prj01-api.git 

mvn archetype:generate -DarchetypeGroupId=org.apache.camel.archetypes -DarchetypeArtifactId=camel-archetype-web -DarchetypeVersion=2.9.0 -DarchetypeRepository=https://repository.apache.org/content/groups/snapshots-group

```

Camel Router WAR Project
========================

This project includes a sample route as as a WAR.
You can build the WAR by running

mvn install

You can then run the project by dropping the WAR into your 
favorite web container or just run

mvn jetty:run

to start up and deploy to Jetty.