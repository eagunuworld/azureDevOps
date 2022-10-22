# myPythonDockerRepo
This a python based app and containerized.
you can clone - https://github.com/akannan1087/myPythonDockerRepo/.
This repo also have Jenkinsfile for automating the following:
- Automating Docker image creation
- Automating Docker image upload
- Automating Docker container provisioning
You can configure pipeline in your Jenkins instance(Docker also installed) by creating a Declarative pipeline.
Make sure you do the following:
1. Create Credentials for connecting to Docker registry
2. Create scripted pipeline using Jenkinsfile from this repo
3. Change registry per your user name = "your_username/mypython-app-may20"
4. Update your credentials ID in Pipeline you are creating.
5. Open port 8096 in Ec2 instance.
###### azure coach devops site ###############
#sonarQube
https://www.cidevops.com/2018/10/create-sonarqube-instance-using.html

#import azure resources
https://www.cidevops.com/2022/07/how-do-you-import-existing-resources.html

#create web app
https://www.coachdevops.com/2022/07/how-to-create-web-app-in-azure-cloud.html

#springboot app
https://www.coachdevops.com/2022/06/how-to-deploy-docker-containers-into.html

#Azure Pipeline for Deployment to AKS Cluster | Azure Pipeline for Docker Container Deployment to AKS
#https://www.youtube.com/watch?v=QWphX6pqqeA
https://www.cidevops.com/2021/11/how-to-deploy-docker-containers-into.html

#How to Deploy Springboot App into AKS cluster using Azure Pipelines |
#Deploy Docker Containers into AKS cluster using Azure Rlease Pipelines |
#Deploy Microservices into AKS cluster using Azure Pipelines
https://www.cidevops.com/search/label/Azure%20DevOps
