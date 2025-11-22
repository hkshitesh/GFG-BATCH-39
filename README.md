## AWS VPC Architecture Diagram

<img width="980" height="672" alt="image" src="https://github.com/user-attachments/assets/0101d9db-251f-46cb-8b6d-3cf80ed98ec4" />

## JDK 17 Download

https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.msi

## Jenkins Download Link

https://www.jenkins.io/download/


## Jenkins Pipeline Plugin

Pipeline: Stage View Plugin

## AWS EKS Connection Command

    aws configure
    
    aws eks --region ap-south-1 describe-cluster --name gfgCluster --query cluster.status
    
    aws eks --region ap-south-1 update-kubeconfig --name gfgCluster
