# nginx-https-redirect-ecs
This is an nignx server that redirects all http traffic to https to be deployed with Amazon ECS. It adds a healthcheck at /elb-health to take advantage of the ECS integration with Amazon ELB - ELB takes care of killing unhealthy ECS containers.
