# java-cli-gradle-cassandra-multi-node-without-ssl-index

## Description
Creates a small database table
called `dog`. This table, `dog`, has been normalized to 3NF.

A java gradle build, that connects to multi node
cassandra database without ssl.

## Tech stack
- docker-compose-wait
- java
- gradle
  - cassandra drivers

## Docker stack
- cassandra:4.0
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Docker setup](https://2much2learn.com/setting-up-cassandra-with-docker/)
- [Cassandra java client](https://github.com/eugenp/tutorials/tree/master/persistence-modules/java-cassandra)
- [Simple cassandra java client](https://raw.githubusercontent.com/oscerd/cassandra-java-example/master/src/main/java/com/github/oscerd/cassandra/SimpleClient.java)
