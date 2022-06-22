# sunsetZman
 This repo contains a javascript application that is packaged into a docker container and deployed to ECS.

 The process is integrated into a CI/CD pipeline using CircleCi that monitors if there is a change to the application and then builds and tests the docker image before deploying to ECS.

 The ECS cluster is hosted on AWS in private subnets behind a load balancer. Route 53 is used to route traffic to the load balancer using an alias record. The application can be accessed from zmanim.danielweiskopf.com

Update: This URL is no longer active
