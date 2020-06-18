# Apache Spark docker image

This repository build docker image for Apache Spark and publish to https://hub.docker.com/repository/docker/opendatastudio/spark


| branch / tag  |  description   | docker image |
|---------|--------|---------|
| master-staroid | snapshot version of 3.1.0 | opendatastudio/spark:v3.1.0-snapshot-\<yyyymmdd>-\<nn> |
| branch-3.0-staroid | snapshot version of 3.0.1 | opendatastudio/spark:v3.0.1-snapshot-\<yyyymmdd>-\<nn> |
| v3.0.0-staroid | official release 3.0.0 | opendatastudio/spark:v3.0.0 |


The image is modified to be used in [Staroid](https://staroid.com).
Take a look [.github/workflows/publish-docker-image.yml](https://github.com/open-datastudio/spark/blob/master-staroid/.github/workflows/publish-docker-image.yml) file to see how this repository build image.
