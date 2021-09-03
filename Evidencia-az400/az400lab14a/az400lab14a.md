#Lab 14a: Ansible with Azure
we will deploy, configure, and manage Azure resources by using Ansible.

Ansible is declarative configuration management software. It relies on a description of the intended configuration applicable to managed computers in the form of playbooks. Ansible automatically applies that configuration and maintains it going forward, addressing any potential discrepancies. Playbooks are formatted by using YAML.

Unlike the majority of other configuration management tools, such as Puppet or Chef, Ansible is agentless, which means that it does not require the installation of any software in the managed machines. Ansible uses SSH to manage Linux servers and Powershell Remoting to manage Windows servers and clients.

In order to interact with resources other than operating systems (such as, for example, Azure resources accessible via Azure Resource Manager), Ansible supports extensions called modules. Ansible is written in Python so, effectively, the modules are implemented as Python libraries. In order to manage Azure resources, Ansible relies on GitHub-hosted modules.

Ansible requires that the managed resources are specified in a designated host inventory. Ansible supports dynamic inventories for some systems, including Azure, so that the host inventory is dynamically generated at runtime.

The lab will consist of the following high-level steps:

- Installing and configuring Ansible on the Azure VM
- Downloading Ansible configuration and sample playbook files
- Creating and configuring a managed identity in Azure AD
- Configuring Azure AD credentials and SSH for use with Ansible
- Deploying an Azure VM by using an Ansible playbook
- Configuring an Azure VM by using an Ansible playbook

##Exercise 1: Deploy, configure, and manage Azure VMs by using Ansible
In this exercise, you will deploy, configure, and manage Azure VMs by using Ansible.

###Task 1: Provision an Azure VM serving as the Ansible control node

![1401](imagesEvidencia14/1401.PNG)

![1402](imagesEvidencia14/1402.PNG)

![1403](imagesEvidencia14/1403.PNG)

###Task 2: Install and configure Ansible on an Azure VM

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

![1415](imagesEvidencia14/1415.PNG)

![1416](imagesEvidencia14/1416.PNG)

![1417](imagesEvidencia14/1417.PNG)

###Task 3: Download Ansible configuration and sample playbook files

![1418](imagesEvidencia14/1418.PNG)

![1419](imagesEvidencia14/1419.PNG)

###Task 4: Create and configure Azure Active Directory managed identity

![1420](imagesEvidencia14/1420.PNG)

![1421](imagesEvidencia14/1421.PNG)

![1422](imagesEvidencia14/1422.PNG)

![1423](imagesEvidencia14/1423.PNG)

![1424](imagesEvidencia14/1424.PNG)

###Task 5: Configure SSH for use with Ansible

![1425](imagesEvidencia14/1425.PNG)

![1426](imagesEvidencia14/1426.PNG)

![1427](imagesEvidencia14/1427.PNG)

![1428](imagesEvidencia14/1428.PNG)

![1429](imagesEvidencia14/1429.PNG)

###Task 6: Create a web server Azure VM by using an Ansible playbook

![1430](imagesEvidencia14/1430.PNG)

![1431](imagesEvidencia14/1431.PNG)

![1432](imagesEvidencia14/1432.PNG)

![1433](imagesEvidencia14/1433.PNG)

![1434](imagesEvidencia14/1434.PNG)

![1435](imagesEvidencia14/1435.PNG)

![1436](imagesEvidencia14/1436.PNG)

![1437](imagesEvidencia14/1437.PNG)

![1438](imagesEvidencia14/1438.PNG)

![1439](imagesEvidencia14/1439.PNG)

###Task 7: Configure an Azure VM by using an Ansible playbook
In this task, you will run another Ansible playbook, this time to configure the newly deployed Azure VM. You will use a playbook that installs a software package httpd and downloads an HTML page from a GitHub repository. Once this is completed, you will have a fully functional Web server.

![1440](imagesEvidencia14/1440.PNG)

![1441](imagesEvidencia14/1441.PNG)
