# 12 microservices Deployment on AWS EKS using Helm and push to artifactory hub

This application  is a sample microservice application you can use as a sandbox to test and learn containerised application orchestration and monitoring techniques. It is not intended to be a comprehensive reference example of how to write a microservices application, although you will better understand some of those concepts by playing with this application . To be clear, the error handling is patchy and there is not any security built into the application.

every microservice has dockerfile assciated with it and EKS manifests,Helm charts are provided in this repository .


This sample microservice application has been built using these technologies:
- NodeJS [([Express](http://expressjs.com/))]
- Java ([Spring Boot](https://spring.io/))
- Python ([Flask](http://flask.pocoo.org))
- Golang
- PHP (Apache)
- MongoDB
- Redis
- MySQL ([Maxmind](http://www.maxmind.com) data)
- RabbitMQ
- Nginx
- AngularJS (1.x)

# EKS Cluster Setup
 checkout EKS cluster setup using eksctl ([EKS.md](https://github.com/deepak4566/12microservices_deployment_inEKS_through_HELM/blob/main/EKS_Setup.md))   
 for setuping EKS cluster with EBS volumes and additional resourses.
 after setupping EKS cluster using Eksctl and provisioning service accounts

# Deploying application through Helm charts
To deploy  application with helm charts u can take help of ([HELM.md](https://github.com/deepak4566/12microservices_deployment_inEKS_through_HELM/blob/main/HELM.md))
and deploy the application using these helm templates  provided in repo ([helm_charts](https://github.com/deepak4566/12microservices_deployment_inEKS_through_HELM/tree/main/HELM/helm))

# push helm to artifact hub
package helm and push to artifact helm 
checkout this blog for push your helm to artifact hub  ([blog]( https://www.devopsschool.com/blog/helm-tutorial-how-to-publish-chart-at-))                                       
