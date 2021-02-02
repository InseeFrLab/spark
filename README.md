# Spark

Docker image for Spark, based on [Bitnami image](https://github.com/bitnami/bitnami-docker-spark), upgrading to Java 11.

## Publication

`inseefrlab/spark` is published on [dockerhub](https://hub.docker.com/r/inseefrlab/spark).

```sh
docker pull inseefrlab/spark:latest
```

## Deployment

`inseefrlab/spark` can be deployed thanks to [Bitnami Helm chart](https://bitnami.com/stack/spark/helm) as follow:

```sh
helm install my-spark bitnami/spark --set image.repository=inseefrlab/spark --set image.tag=latest
```
