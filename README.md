[![BUILD CICD-MINIO IMAGE](https://github.com/adrian0cg/minio-cicd/actions/workflows/build.yml/badge.svg)](https://github.com/adrian0cg/minio-cicd/actions/workflows/build.yml)
# MinIO (CICD/GitHub Actions)
This respository builds a MinIO container image for the express purpose of use for CI/CD pipelines, specifically in GitHub Actions workflows, as Github Actions do not currently allow custom commands to be passed to services. The image is built using the official MinIO Docker image as the base image.

The container is rebuilt automatically on the 15th of every month, pulling the latest MinIO image. It is tagged with "latest" and the latest MinIO version.
