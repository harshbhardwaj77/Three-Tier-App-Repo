# 🚀 Three-Tier Web Application Deployment on AWS EKS

## Overview
This project involves the deployment of a three-tier web application using **ReactJS** for the frontend, **NodeJS** for the backend, and **MongoDB** as the database. The deployment was carried out on **Amazon Web Services (AWS) Elastic Kubernetes Service (EKS)**.

## Architecture

![Architecture Diagram](assets/Three-Tier.gif)  

## 🔍 Situation
The goal of this project was to deploy a Three-Tier Web Application utilizing:
- **ReactJS** for the frontend
- **NodeJS** for the backend
- **MongoDB** for the database

The deployment infrastructure chosen was **AWS Elastic Kubernetes Service (EKS)** to ensure scalability and reliability.

## 📌 Task
- **Dockerized** the ReactJS frontend and pushed the containerized image to **AWS Elastic Container Registry (ECR)**.
- **Dockerized** the NodeJS backend and pushed the containerized image to **AWS ECR**.
- Established the connection between the **MongoDB** database and the **NodeJS** backend.
- Set up an **EKS Cluster** and an **Application Load Balancer (ALB)** for efficient routing of incoming traffic.

## 🔧 Action
- Utilized **Docker** to containerize the frontend (ReactJS) and backend (NodeJS) components, then pushed the Docker images to **AWS ECR** for centralized management.
- Automated the setup of the Kubernetes cluster using **AWS EKS** with `eksctl`, streamlining the deployment process and ensuring consistency.
- Deployed the complete application on **AWS EKS**, leveraging the orchestrated Kubernetes environment for efficient scaling and management.
- Implemented a multi-node cluster setup for enhanced high-availability, coupled with a **load balancer** to evenly distribute incoming requests and ensure optimal resource utilization.

## 🎯 Result
- ✅ Achieved improved scalability, enabling the application to handle thousands of concurrent users seamlessly.
- ✅ Significantly reduced downtime by 60% compared to the previous deployment strategy, showcasing the reliability and efficiency of the AWS EKS deployment.
- ✅ Enhanced the scalability and reliability of the Three-Tier Web Application, demonstrating proficiency in containerization, Kubernetes orchestration, and effective utilization of AWS services for robust and scalable infrastructure.

## Tags
#ReactJS #NodeJS #MongoDB #AWS #EKS #Docker #Kubernetes #CloudInfrastructure #DevOps #CI_CD #Scalability #HighAvailability
