# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
<br>
<br>
Article CMS is a small and simple application. App Service is sufficient for this type of application. 
**Costs**
I can start small and grow as needed. Starting cost for App Service can be very little. VMs are more expensive and they can be more involved, complex and time consuming for the developers than other compute options. In App Service, I have limited access to the host server and there are some hardware limitations like 14GB RAM and 4 vCPU cores per instance but these are fine for such a small and simple application.

High availability, auto-scaling and support of both Linux and Windows environments.
Continuous deployment model using GitHub, Azure DevOps, or any Git repo.
Vertical or Horizontal scaling. Vertical scaling increases or decreases resources allocated to our App Service, such as the amount of vCPUs or RAM, by changing the App Service pricing tier. Horizontal scaling increases or decreases the number of Virtual Machine instances our App Service is running.

<br>
<br>
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
