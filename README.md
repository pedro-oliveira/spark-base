# Spark Base Image

This repository contains the Dockerfile with the instructions to build a base image for running Spark jobs. It will serve as a building block for the [py-spark](https://github.com/pedro-oliveira/py-spark) and [r-spark](https://github.com/pedro-oliveira/r-spark) images that add Python and R, respectively, to the stack.

This image is built on top of the Java 8 based on Alpine image maintained by OpenJDK - **openjdk:8u151-jre-alpine**.

**Note:** Scala is not installed in this image, thereby you cannot run Scala interactive sessions using the `/bin/spark-shell`.