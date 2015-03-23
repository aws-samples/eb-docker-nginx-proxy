# Elastic Beanstalk Multi Container PHP-FPM + Nginx Demo App

This demo app shows you how to run a simple PHP application using the [PHP-FPM](https://registry.hub.docker.com/u/library/php/) and [Nginx](https://registry.hub.docker.com/u/library/nginx/) Docker images from the official Docker library.

## Run the App
Follow the steps below to deploy this application to an Elastic Beanstalk Multi-container Docker environment. Accept the default settings unless indicated otherwise in the steps below:

1. Download the ZIP file from the [Releases section](https://github.com/awslabs/eb-docker-nginx-proxy/releases) of this repository.
2. Login to the [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk)
3. Click 'Create New Application' and give your app a name and description
4. Click 'Create web server' and select an IAM instance profile to use.<br>*Note: Please ensure the IAM instance profile you select has the necessary permissions. For more information, see [Container Instance Role](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_ecs.html#create_deploy_docker_ecs_role)*
5. Choose 'Multi-container Docker' in the 'Predefined configuration' dropdown and click `Next`
6. Upload the ZIP file downloaded in step 1
7. Review and launch the application
