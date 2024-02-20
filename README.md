# AWS-EKS-Pokemon-Pokedex-App

In this project I deployed a Python-based Pokémon Pokédex application on AWS Elastic Kubernetes Service (EKS) using eksctl for cluster creation and management, ensuring a scalable and secure environment. Utilized Kustomize to manage the application's deployment and service configurations, opting for a LoadBalancer service type to efficiently distribute traffic. Integrated a custom domain name for the application through AWS Route 53, enhancing accessibility and providing a professional touch. The combination of EKS, eksctl, Kustomize, and Route 53 streamlined the deployment process, offering a robust and user-friendly platform for Pokémon enthusiasts.

Link to website: http://pokedex.reggiestestdomain.com/

## Architecture Breakdown

The Kubernetes Cluster is broken down into the architecture below:

![kubernetespython](https://github.com/rjones18/Images/blob/main/EKS%20Cluster%20(2).png)
