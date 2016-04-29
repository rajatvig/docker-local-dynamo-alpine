![](https://circleci.com/gh/rajatvig/local-dynamo-alpine.svg?style=shield&circle-token=813d0fbd52a9d088e588984a0d52931ea4154ea9)
[![](https://imagelayers.io/badge/rajatvig/local-dynamo-alpine:latest.svg)](https://imagelayers.io/?images=rajatvig/local-dynamo-alpine:latest 'Get your own badge on imagelayers.io')

# Overview

This image contains a copy of the Local DynamoDB using JDK based off https://hub.docker.com/r/delitescere/jdk/.

# How-to/usage

In order to use this, simply run:

docker run -d -t -p 8000:8000 rajatvig/local-dynamo-alpine