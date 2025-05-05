###################################################
# Stage: base
# 
# This base stage ensures all other stages are using the same base image
# and provides common configuration for all stages, such as the working dir.
###################################################
FROM ubuntu:latest AS base
RUN apt-get update
RUN apt-get upgrade -y
CMD ["echo", "Hello, World!"]