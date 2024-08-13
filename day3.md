# 30 Days AWS Challenge
## Understanding AWS core services
### Objectives 
AWS offers a broad set of global cloud based products including compute, storage, databases, analytics,networking, mobile, developer tools, management tools, security and enterprise applications.These services help you build elastic, agile, relient architecutes.

### Monolithic Architecture
Monolithic architecture is a software design pattern where all components of an application are integrated into a single, unified codebase. This structure allows for easier development and deployment in the early stages but can become complex and difficult to manage as the application grows. Scaling and updating parts of the application often require redeploying the entire system, making it less flexible compared to microservices architecture.

### Microservice Architecture
Microservice architecture is a design approach where an application is composed of small, independent services that communicate with each other through APIs. Each service is responsible for a specific functionality and can be developed, deployed, and scaled independently, offering greater flexibility and resilience. This architecture allows for more efficient scaling and easier maintenance but can introduce complexity in managing inter-service communication and data consistency.

### Types of Services
- Managed Services
  - Managed services are like hiring a team to take care of your IT needs. AWS handles most of the heavy lifting, like maintenance and updates, so you can focus on your core business without worrying about the underlying infrastructure.

- Fully managed services
  - Fully managed services take things a step further by handling all aspects of the service. AWS manages everything, from scaling and backups to security and performance optimization, so you don’t have to do anything but use the service.

- Serverless Services
  - Serverless services allow you to run code without provisioning or managing servers. AWS automatically scales the resources and you only pay for the compute time you use. This is ideal for applications with unpredictable traffic since you don’t need to worry about over- or under-provisioning resources.

### Amazon VPC (Virtual Private Cloud)
Amazon VPC lets you create a private network within AWS, where you can launch AWS resources in a virtual network that you define. Here are some key features:

- Subnets:

  - Public Subnets: These are subnets that are accessible from the internet. You’d typically place resources like web servers in public subnets.
  - Private Subnets: These are isolated from the internet and are used for resources that shouldn’t be publicly accessible, like databases.
- Security:

  - Amazon VPC provides advanced security features, allowing you to create security groups and network access control lists (ACLs) to control inbound and outbound traffic.
- Internet Gateway:

  - This allows your VPC to communicate with the internet. It’s used to enable instances in public subnets to connect to the outside world.
- NAT Gateway:

  - ACLs: The NAT Gateway allows instances in private subnets to connect to the internet without exposing them to inbound traffic from the internet.
- Peering:

  - VPC peering allows you to connect two VPCs, enabling resources in both VPCs to communicate with each other as if they were on the same network.
- VPN Connections:

  - VPN connections let you securely connect your on-premises network to your AWS VPC, creating a secure tunnel over the internet.
 
### Benefits of Amazon VPC
**Advanced Security:** Amazon VPC provides features like inbound and outbound filtering, making it easy to secure your applications.

**Less Time on Setup:** AWS handles much of the heavy lifting, so you spend less time managing infrastructure and more time building your applications.

**Customization:** You can choose your IP ranges, create your own subnets, and configure route tables to fit your needs.