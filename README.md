# Azure Starter Pack
Writing a post on top 10 skills needed for .NET teams to get started on Azure in 2021 - skills are both Azure services and related tools/services. This will be somewhat controversial because less focus on shiny stuff *cough  k8s*

.NET Team, SQL, On-prem to cloud, TFS

Go
1. Web Apps
No brainer. Quickly spin up a website, right-click publish from Visual Studio, deploy containers, even create a WordPress blog, host a SignalR Hub and so on

2. SQL 
SQL Server is database of choice for most .NET teams. Offers single instance and also pooled/managed for flexibility. Great query insights tool

3. Azure Storage
So you store relational data with SQL but where do you store various files and unstructured data? Azure storage not only stores files and blobs but also offers cheap table storage and queues for incoming messages

4. Azure DevOps
Yes I know Microsoft bought GitHub and there are rumors about Azure DevOps' being replaced by GitHub but if you're coming from an on-prem TFS type environment this offers the easiest ramp-up. Also classic (GUI) pipelines are easier to learn and test for those new to the concept.

5. ARM
This is the underlying laguage of Azure resources. I won't let a starter move to Terraform without understaning ARM

6. Azure Powershell/CLI
To keep things simple, teams with Windows background go with Powershell and Linux with CLI. No previous preference? Go with CLI

7. Azure Functions
What's not to like? Bring your code and run on unlimited scale. Hook it up to a bunch of connectors. But in order to work with Functions it would help to become familiar with some of the foundational concepts listed earlier.

8. API Management
Leverage this early on when using APIs. Mocking, versioning, rate limiting, blocking, built-in security features all lay a good foundation to managing APIs

9. Key Vault
Starts storing secrets, keys, certs. Don't end up on a news story because you posted an Instagram selfie with database creds in the background

10. Monitor
No point in deploying anything if you cannot watch it in prod and respond. App Insights, Log Analytics, alerts and other services help keep an eye on the deployed applications.

Next: List of Azure-related things you should know after getting started with the top 10.

11. Virtual machines
Most Azure service (even PaaS) run on VMs. For instance, you may have to configure a Databricks instance and will need to know the difference between a D-series and E-series VM. Helps to know the basics of VMs in Azure

12. Logic Apps
Once you start to move to Azure you will realize that actions like querying a database on a periodic basis and sending an email may not necessarily need you to spin up and maintain a VM. Logic Apps with its incredible range of connectors helps easily setup and run tasks like these on a periodic basis. Warning: addictive

13. Cosmos DB
Store non-relational data in document, graph, columnar and other formats. Incredible performance and scale. Functions and Cosmos DB can combine for some cool serverless use cases 

14. Data Factory
Speaking of data, ADF offers a convenient, scaleable and programmable option to import and export a variety of data

15. Cognitive services
Add “AI” to apps - vision, language, speech - using Cognitive Services API

16, 17, 18 = Event Hub, Event Grid, Service Bus
Kind of similarlish but also different. Handle various scenarios of events and messaging

19. Power BI
Gotta query and visualize all that data in Azure. Did you know that you can even hook up monitor log in Power BI? Connects to a variety of data sources 

20. Azure Kubernetes Service
Not for beginners in Azure but this is where most greenfield workloads are starting to be deployed these days. As more dev teams shift to containerized workloads, this is where the roaring 20s will be
