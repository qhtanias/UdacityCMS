# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*

Azure App services:
-Azure Web Apps is a fast and simple way to create web apps using ASP.NET, Java, Node.js or PHP.It has built-in CI/CD integration and has zero-downtime deployments. Its take away most of the complexity and lets us concentrate more on the application itself.
-(which, until this past April, was called Azure Websites) is a managed platform. This means that Azure takes care of application deployment and management, while the developer only needs to concentrate on app development. Azure App Service supports applications defined by Azure as “Web Apps”, “Mobile Apps”, “API Apps”, and “Logic Apps”.

Azure virtual machine:
-Azure Virtual Machines let us provision Windows or Linux VMs in seconds, can be deployed with own VM image or images from the Azure Marketplace, ability to scale from one to thousands of VM instances in minutes with Azure Virtual Machine Scale Sets.

-give you full control over application management and deployment. For projects that may require substantial modifications to the technology stack in the future, or for people worried about being locked into a single vendor, the extra work required to launch and maintain Virtual Machines might be worth it.

- *Analyze costs, scalability, availability, and workflow*

Analyze costs:

scalability:

availability:

workflow:



- *Choose the appropriate solution (VM or App Service) for deploying the app*
App services.

- *Justify your choice*
As our application is a not business critical and dosent require any special control over the deployment, I used App Service. In future I might add more functionality to the app and we might require better control over the deployment or decide to write business critical articles or ultimate usage of the app might increase. In that case I would migrate to Virtual Machines and use Higher Tier SQL database for better access and security. New Plan will be according to the budget threshold.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

