# nginx-https-redirect-ecs
[![License: MIT](https://img.shields.io/github/license/ging/fiware-idm.svg)](https://opensource.org/licenses/MIT)
[![Docker badge](https://img.shields.io/docker/pulls/ucabvas/nginx-https-redirect-ecs.svg)](https://hub.docker.com/r/ucabvas/nginx-https-redirect-ecs/)

This is an nignx server that redirects all http traffic to https to be deployed with Amazon ECS. It adds a healthcheck at /elb-health to take advantage of the ECS integration with Amazon ELB - ELB takes care of killing unhealthy ECS containers.
