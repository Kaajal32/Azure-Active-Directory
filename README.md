<h2>Description</h2>
SIEM (Security Information and Event Management System) is a tool security professionals use to analyze logs from different sources such as Firewalls, IDS/IPS, and much more. It helps security professionals to monitor, prioritize, and remediate threats in real-time. Azure Sentinel (Microsoft Sentinel) is one such SIEM cloud-based tool providing capabilities such as security analytics, threat intelligence, threat response, and more in a single platform.  In this project, we will leverage Azure resources like Log Analytics workspace and use KQL query to detect security events in the Windows operating system. 

<h2>Part 1: Setting Up Lab Resources</h2>
1. Created a new Account in Azure. Azure Subscription 1 with $200 credits was provided for free. For this project, a resource group with the name:labgroup was created.
<img src = "images/1.png" height = 400, width = 500>
2. Created a new Virtual Machine to install Windows 10 Pro operating system using the Resources: labgroup. Virtual Machine Name: labvm
<img src = "images/2.1.png" height = 400, width = 500> <img src = "images/2.1.png" height = 400, width = 500> <img src = "images/2.2.png" height = 400, width = 500> <img src = "images/2.3.png" height = 400, width = 500> <img src = "images/2.4.png" height = 400, width = 500>
3. Here, if you look at our inbound rule you can see that that inbound RDP traffic is allowed from any source to any destination. RDP is necessary to access our VM. However, with this current setting, anyone who obtains our public IP (which can be possibly be obtained via network scan) can potentially connect to the VM as this is public public-facing which makes VM vulerable to brute force or password spray attack. So, in Microsoft Azure Sentinel, we enabled all the plans for 

<h2>Part 2: Getting Data into Sentinel </h2>
<h2>Part 3: Generating Security Events </h2>
<h2>Part 4: Creating Scheduled Task and Writing Analytic Rule </h2>
<h2>Part 5:  MITRE ATT&CK: </h2>
<h2> Learned Concepts: </h2>
