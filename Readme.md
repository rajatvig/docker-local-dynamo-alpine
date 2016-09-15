[![Build Status](https://travis-ci.org/rajatvig/docker-local-dynamo-alpine.svg?branch=master)](https://travis-ci.org/rajatvig/docker-local-dynamo-alpine)
[![](https://images.microbadger.com/badges/image/rajatvig/local-dynamo-alpine.svg)](http://microbadger.com/images/rajatvig/local-dynamo-alpine "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/rajatvig/local-dynamo-alpine.svg)](http://microbadger.com/images/rajatvig/local-dynamo-alpine "Get your own version badge on microbadger.com")

# Overview

This image contains a copy of the Local DynamoDB using JDK based off https://hub.docker.com/r/delitescere/jdk/.

# How-to/usage

In order to use this, simply run:

docker run -d -t -p 8000:8000 rajatvig/local-dynamo-alpine:latest
