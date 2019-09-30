# **hive**
___

### Description
___

This image runs the [*Cloudera CDH Hive*](https://www.cloudera.com/products/open-source/apache-hadoop/key-cdh-components.html) on a Centos 7 Linux distribution.

You can pull it with:

    docker pull comchangs/hive

You can also find other images based on different Apache Hive releases, using a different tag in the following form:

    docker pull comchangs/hive:[hive-release]-[cdh-release]

For example, if you want latest version you can pull the image with:

    docker pull comchangs/latest

Run with Docker Compose:

    docker-compose -p comchangs up

Stop with Docker Compose:

    docker-compose -p comchangs down
