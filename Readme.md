[![Build Status](https://travis-ci.org/rajatvig/docker-local-dynamo-alpine.svg?branch=master)](https://travis-ci.org/rajatvig/docker-local-dynamo-alpine)
[![](https://imagelayers.io/badge/rajatvig/local-dynamo-alpine:latest.svg)](https://imagelayers.io/?images=rajatvig/local-dynamo-alpine:latest 'Get your own badge on imagelayers.io')

# Overview

This image contains a copy of the Local DynamoDB using JDK based off https://hub.docker.com/r/delitescere/jdk/.

# How-to/usage

In order to use this, simply run:

docker run -d -t -p 8000:8000 rajatvig/local-dynamo-alpine
