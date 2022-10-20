# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
VM:
there are cost limiotation which it is more expansive from app service, but the cost is low comparing purchasing and mantainig hardware. for scalability using Virtual Machine Scale Sets and Load Balancers.
in addition to using  multiple VMs can be grouped to provide high availability, scalability, and redundancy. VM support both windows and linux operating system,and the user have the Full control of the VM because it is consider as an IAAS.




App service:
Cost depend on the plan, but it less expansive than vm, and there are two type of scalling vertical and horizontal scalling.it have high availability, auto-scaling, and support of both Linux and Windows. it of supported multiple programming languges and can be deploy using GitHub, Azure DevOps, or any Git repo.

- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I will choose App service, because it have lower cost from the VM cost , and it have a quick scaling with using light weight API and support using python and deploying with github.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

when the web application get well known and have many users we should choose virtual machine.


