# Docker Android CI

Docker image to build Android apps in a CI environment

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to build an Android app into an APK. Currently being used with [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines), but should meet the requirements for most CI systems.

## Details

### Base Image

* [uber/android-build-environment](https://hub.docker.com/r/uber/android-build-environment/) - The latest Android build environment used by Uber
  
### Additional Packages

* Android Support Repo
