# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

For this project, I chose the App Service over a VM due to its ease of management, especially for those that are not as well versed in this web application development. By selecting the VM path it provided me with more control over the developmental phase. In order to make this decision I took into consideration cost, scalability, availability, and workflow, the App Service was the better option. 

### Cost: The App Service is generally more cost-effective compared to a VM. With the App Service, you only pay for the resources you use, and there are no additional costs for managing the underlying infrastructure. This can lead to significant savings, especially for smaller projects or those with variable workloads.

### Scalability: The App Service offers built-in scalability features that allow your application to handle varying levels of traffic without manual intervention. You can easily scale up or down based on demand, ensuring that your application remains responsive and performs well under different conditions. This automatic scaling capability is a major advantage over a VM, where you would need to manually configure and manage scaling.

### Availability: The App Service provides high availability out of the box, with features such as load balancing and automatic failover. This ensures that your application remains accessible to users even in the event of hardware failures or other issues. In contrast, achieving high availability with a VM requires additional configuration and management, which can be complex and time-consuming.

### Workflow: The App Service simplifies the development and deployment workflow by offering integrated tools and services. This includes continuous integration and deployment (CI/CD) pipelines, monitoring and diagnostics, and built-in support for popular development frameworks. These features streamline the development process and reduce the time and effort required to deploy and maintain your application.

### Assess app changes that would change your decision.

Need for Granular Control: If the application requires more granular control over the infrastructure, such as custom configurations, specific hardware requirements, or specialized software installations, a VM might be a better option. This is because VMs offer more flexibility and control over the operating system and environment.

High Resource Demands: If the application has high resource demands that exceed the capabilities of the App Service, such as intensive computational tasks or large-scale data processing, a VM might be more appropriate. VMs can be scaled to meet higher resource requirements and can be customized to handle specific workloads.

Compliance and Security Requirements: If the application needs to meet strict compliance and security requirements that are not fully supported by the App Service, a VM might be necessary. VMs allow for more control over security configurations and can be tailored to meet specific compliance standards.

Legacy Applications: If we are working with legacy applications that are not compatible with the App Service or require specific dependencies that are not supported, a VM might be the only viable option. VMs can run older operating systems and software that may not be supported by modern managed services.

Cost Considerations: While the App Service is generally cost-effective, there may be scenarios where a VM could be more economical, especially for applications with predictable and consistent workloads. In such cases, the cost of running a VM might be lower than using a managed service.
