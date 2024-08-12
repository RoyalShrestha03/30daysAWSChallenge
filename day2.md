# 30 Days AWS Challenge
## Introduction to Cloud Computing
### AWS Offerings

Compute:

EC2 (Elastic Compute Cloud): Provides scalable virtual servers where you can launch and manage instances with various configurations, paying only for what you use.

S3 (Simple Storage Service): Offers scalable object storage with high durability and availability, ideal for storing and retrieving any amount of data.

RDS (Relational Database Service): Provides managed relational databases with automated backups, scaling, and patching.

Analytics:AWS provides analytics services like Amazon Redshift for data warehousing and Amazon Athena for serverless SQL queries on S3 data, enabling scalable and efficient data analysis.

Networking & content delivery:
AWS offers networking and content delivery services like Amazon VPC for creating isolated networks and Amazon CloudFront for delivering content globally with low latency through a content delivery network (CDN).

Developer Tools:
AWS provides developer tools like AWS CodePipeline for automating software release processes, AWS CodeBuild for building and testing code, and AWS CodeDeploy for automating application deployments across various environments.

Machine Learning:
AWS offers machine learning services like Amazon SageMaker for building, training, and deploying machine learning models, and AWS Rekognition for image and video analysis.

Internet of Things:
AWS provides IoT services such as AWS IoT Core for securely connecting and managing IoT devices, and AWS IoT Analytics for processing and analyzing IoT data at scale. These services help in building and managing IoT solutions efficiently.

### Benefits of AWS

On demand access:
you can access cloud based services whenever you need it.

Pay as you go pricing:
you pay for the service only for the time you use it.

No upfront capital expenses:
Enterprises, startups, small and medium size business and customers in public sector can access building block that they need.

Tool box of high end services:
with aws you have access to tool box of services you might not otherwise use, such services includes machine learning,IoT and high end security sercvices.

## AWS Global Infrastructure

### Planning for failure
When building your architecture in the cloud, it is important to plan for failure. When you build your architecture, you want to have a plan in place to resolve any failure that might occur.

**Storage:**
When a file is stored in Amazon S3,the file is redundantly copied into every Availability Zone in that Region.If one Availability Zone goes down, you still have two copies of the file available for  you to use.

**compute:**
It is a best practice to spread out your computing resources across multiple Availability Zones to gurantee high availability.So, if one Availability Zone goes down,your architecture is sitll up and running.

**Database:**
You can configure your database for Multi-AZ deployment.If your Availability Zone with your primary databases fails, one of the standby databases in a healthy Availability Zone automatically becomes your new primary database.Therefore, your architecture is still functioning.

### AWS Global Infrastructure Benefits
**Performance:**
The Aws Global Infrastructure offers high-performing, low-latency cloud inftastructure with virtually unlimited capacity, which provides high availability.

**Availability:**
Availability Zones are designed for physical redundancy and to provide resilience.They provide uninterrupted performance,even in the event of power outages,internet downtime and other natural disasters.

**Security:**
The infrastructure is monitored 24/7 to help ensure the confidentiality,integrity,and availability of AWS customers' data.They can encrypt their data, move it, and manage retention.

**Reliability:**
The AWS Global infrastructure is designed and build for redundancy and reliability, from regions to networking links to load balancers to routers to firmware.

**Low Coast:**
The AWS Global infrastructure provides the industry's most extensive data center footprint.

### Shared responsibility

Customers are responsible for the security of everything that they create and put IN the AWS Cloud.

AWS manages the security OF the cloud, specifically the physical infrastructure that hosts your resources.

### Total Cost of Ownership
The Total Cost Of Ownership(TCO) is a finantical metric that is used to estimate and compare direct and indirect costs of a product or a sercvice.


