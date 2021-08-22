#Lab 14b: Automating infrastructure deployments in the Cloud with Terraform and Azure Pipelines
Terraform is a tool for building, changing and versioning infrastructure. Terraform can manage existing and popular cloud service providers as well as custom in-house solutions.

Terraform configuration files describe the components needed to run a single application or your entire datacenter. Terraform generates an execution plan describing what it will do to reach the desired state, and then executes it to build the described infrastructure. As the configuration changes, Terraform is able to determine what changed and create incremental execution plans to execute.

In this lab, we will learn how to incorporate Terraform into Azure Pipelines for implementing Infrastructure as Code.
##Exercise 0: Configure the lab prerequisites - set up the prerequisites for the lab, which consist of the preconfigured Parts Unlimited team project based on an Azure DevOps Demo Generator template.

###Task 1: Configure the team project - we will use Azure DevOps Demo Generator to generate a new project based on the Terraform template.

![1401](imagesEvidencia14/1401.PNG)

##Exercise 1: Automate infrastructure deployments in the cloud with Terraform and Azure Pipelines
###Task 1: Examine the Terraform configuration files
we want to create an Azure Resource group, App service plan and App service required to deploy a website. We have added the Terraform file to source control repository in the Azure DevOps project so you can use it to deploy the required Azure resources.

![1402](imagesEvidencia14/1402.PNG)

![1403](imagesEvidencia14/1403.PNG)

###Task 2: Build your application using Azure CI Pipeline - build your application and publish the required files as an artifact called drop.

![1404](imagesEvidencia14/1404.PNG)

![1405](imagesEvidencia14/1405.PNG)

![1406](imagesEvidencia14/1406.PNG)

![1407](imagesEvidencia14/1407.PNG)

![1408](imagesEvidencia14/1408.PNG)

![1409](imagesEvidencia14/1409.PNG)

![1410](imagesEvidencia14/1410.PNG)

![1411](imagesEvidencia14/1411.PNG)

![1412](imagesEvidencia14/1412.PNG)

![1413](imagesEvidencia14/1413.PNG)

![1414](imagesEvidencia14/1414.PNG)

###Task 3: Deploy resources using Terraform (IaC) in Azure CD pipeline
we will create Azure resources using Terraform as part of our deployment pipeline and then deploy the PartsUnlimited application to an Azure app service web app provisioned by Terraform.

![1415](imagesEvidencia14/1415.PNG)

![1416](imagesEvidencia14/1416.PNG)

![1417](imagesEvidencia14/1417.PNG)

![1418](imagesEvidencia14/1418.PNG)

![1419](imagesEvidencia14/1419.PNG)

![1420](imagesEvidencia14/1420.PNG)

![1421](imagesEvidencia14/1421.PNG)

![1422](imagesEvidencia14/1422.PNG)

![1423](imagesEvidencia14/1423.PNG)

![1424](imagesEvidencia14/1424.PNG)

![1425](imagesEvidencia14/1425.PNG)

![1426](imagesEvidencia14/1426.PNG)

![1427](imagesEvidencia14/1427.PNG)

![1428](imagesEvidencia14/1428.PNG)

![1429](imagesEvidencia14/1429.PNG)

![1430](imagesEvidencia14/1430.PNG)

![1431](imagesEvidencia14/1431.PNG)

![1432](imagesEvidencia14/1432.PNG)

![1433](imagesEvidencia14/1433.PNG)

![1434](imagesEvidencia14/1434.PNG)
