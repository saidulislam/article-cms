# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
<br>
<br>
Article CMS is a small and simple web application. Azure App Service is an HTTP-based service for hosting web applications and it is sufficient for this type of application. 
<br>
<br>
Costs
<br>
I can start small and grow as needed. Starting cost for App Service can be very little. VMs are more expensive and they can be more involved, complex and time consuming for the developers than other compute options. In App Service, I have limited access to the host server and there are some hardware limitations like 14GB RAM and 4 vCPU cores per instance but these are fine for such a small and simple application.
<br>
<br>
Scalability
<br>
App Service provides auto-scaling (Vertical or Horizontal scaling) and continuous deployment model using GitHub, Azure DevOps, or any Git repo. It is possible to have multiple VMs be grouped to provide high availability, scalability, and redundancy but all these will require a lot more hands approach compared to the App Service option. 
<br>
<br>
Availability
<br>
Again, it is possible to have multiple VMs be grouped to provide high availability, scalability, and redundancy but all these will require a lot more hands approach compared to the App Service option. With App Service option, developers will be hands off and they won't have to worry about it. App Serice provides high availability.
<br>
<br>
Workflow
<br>
Workflow to setup and deploy a web app is simple and quicker with App Service compared to the VM approach. With the VM approach, developer will have to provision VM, setup firewall/network rules, transfer the app files, install all the dependencies and run the app. With the App Service approach, developer will instantiate the service, either depploy the app from local box via Azure CLI or put the latest code in Github or similar and itegrate with the App Service for continuous deployment. All the steps are done through the web interface.
<br>
<br>
<br>
<br>
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
<br>
<br>
*If the application becomes large and complex, and I need more flexibilities in terms of configurations - security, network rules, more memory and cpus.
*Increase in the number of users and usage.
*Bigger budget with more resources to manage VMs, Databases, and complex network rules.



