# go.cd server Docker image

Dockerfile for the [Go.cd](http://go.cd) continuous integration server.

This builds the Go server. You will probably also want [agents](https://github.com/kewubenduben/docker-gocd-agent).

## Run it

    docker pull kewubenduben/docker-gocd-server
    docker run -d -p 8153:8153 -name gocd-server kewubenduben/docker-gocd-server