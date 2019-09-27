# **hive**
___

### Description
___

This image runs the [*Cloudera CDH Hive*](https://www.cloudera.com/products/open-source/apache-hadoop/key-cdh-components.html) on a Centos 7 Linux distribution.

You can pull it with:

    docker pull comchangs/hive

You can also find other images based on different Apache Hive releases, using a different tag in the following form:

    docker pull comchangs/hive:[hive-release]-[cdh-release]

For example, if you want Apache Hive release 1.1.0 you can pull the image with:

    docker pull comchangs/hive:1.1.0-cdh5.11.1

Run with Docker Compose:

    docker-compose -p parrot up

Stop with Docker Compose:

    docker-compose -p parrot down


### Available tags:

- Apache Hive 2.1.1 ([latest](https://github.com/comchangs/docker-hive/blob/latest/Dockerfile), [2.1.1](https://github.com/comchangs/docker-hive/blob/2.1.1/Dockerfile))
- Apache Hive 1.2.2 ([1.2.2](https://github.com/comchangs/docker-hive/blob/1.2.2/Dockerfile))
- Apache Hive 1.1.0-cdh5.11.1 ([1.1.0-cdh5.11.1](https://github.com/comchangs/docker-hive/blob/1.1.0-cdh5.11.1/Dockerfile))
