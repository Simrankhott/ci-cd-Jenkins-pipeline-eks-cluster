This project provides instructions and steps to deploy a Spring application using Kubernetes ConfigMap for managing configuration and reloading the configuration without restarting the application.

Prerequisites
Before getting started, ensure you have the following prerequisites:

Amazon Linux 2 instance (t2.micro) or a similar environment.
. Git installed on the system.
. Java installed on the system.
. Maven installed on the system.
. Jenkins installed on the system.
. Docker installed on the system.
. Python installed on the system.
. Ansible installed on the system.
. Deployment Steps

Follow these steps to deploy the Spring application:

. Clone the code from the GitHub repository.

. Build the Maven artifact.

. Build the Docker image for the Spring Boot application.

. Set all secrets 

Log in to Docker.

. Push the Docker image to Docker Hub.

. Deploy the Spring application using Kubernetes ConfigMap.

. Check the deployments, pods, and services.
