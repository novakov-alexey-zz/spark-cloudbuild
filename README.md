# Google Cloud Build config for Apache Spark

It is build config to build Spark Docker image based on existing web archive of Spark distribution.

There are two Cloud Build parameters:

_IMAGE_TAG - tag which will used for newly built image. For example: v2.4.3
_DIST_URL - URL to Spark distribution. For example: https://archive.apache.org/dist/spark/spark-2.4.3/spark-2.4.3-bin-hadoop2.7.tgz