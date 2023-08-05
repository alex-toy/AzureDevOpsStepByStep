# Azure DevOps Step by Step

When working on ASP.NET Core applications, it's important to have a reliable and automated CI/CD pipeline. We will see how to create a CI/CD pipeline using Azure DevOps, and deploy applications to the cloud.


## Azure DevOps basics


### General picture

- how the azure board is mapped to the general workflow of devops
<img src="/pictures/devops.png" title="general picture of devops"  width="900">
<img src="/pictures/devops2.png" title="general picture of devops"  width="900">


### Create Pipeline

- in the **Repo** section, add your repo
<img src="/pictures/pipeline0.png" title="pipeline"  width="900">

- in the **Pipeline** section, choose your repo
<img src="/pictures/pipeline.png" title="pipeline"  width="900">

- select framework
<img src="/pictures/pipeline2.png" title="pipeline"  width="900">

- in the **Project Settings** section, create an **Agent Pool**
<img src="/pictures/pipeline3.png" title="pipeline"  width="900">

- create an **Agent Pool**
<img src="/pictures/pipeline4.png" title="pipeline"  width="900">

- execute the self-hosted **Agent Pool**
<img src="/pictures/pipeline5.png" title="pipeline"  width="900">

- create a personal access token and use it
<img src="/pictures/pipeline6.png" title="pipeline"  width="900">

- run the pipeline on the self-hosted agent
<img src="/pictures/pipeline7.png" title="pipeline"  width="900">



## Azure DevOps CI/CD Pipelines

In this Azure DevOps CI/CD Pipelines project, we will see how to set up a CI/CD pipeline in Azure DevOps for ASP.NET Core applications.

### Settings

- create web app
<img src="/pictures/cicd_webapp.png" title="web app"  width="900">

- create pipeline using the classic editor
<img src="/pictures/cicd.png" title="pipeline"  width="900">
<img src="/pictures/cicd2.png" title="pipeline"  width="900">