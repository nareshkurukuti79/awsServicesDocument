# AWS Services Document by Naresh Kurukuti

## 1. Amazon EC2
Amazon EC2 offers the broadest and deepest compute platform with a choice of processors, storage, operating systems, networking, and purchase model.  The SLA commitment of 99.99% availability of each Amazon EC2 region.

##### Pricing types of EC2 Instances:
1. **On-Demand Instances** ➡️	 You pay for the compute capacity by the hour or by the second, it’s preferable for without any long term commitments and no upfront cost.
2. **Spot Instances** :arrow_right: Up to 90% off the on-demand price, it’s preferable urgent computing needs for a large amount of additional capacity.
3. **Saving Plans** :arrow_right: The Saving plans provides savings up to 72% on your AWS compute usage. And you can signup 1year or 3-year term, it is the same as Reserved Instances.
4. **Reserved Instances** :arrow_right: It will provide you with a significant discount up to 75% compared to On-Demand pricing, Reserved instances are assigned to specific availability zones, Customers can commit using EC2 instances 1year or 3year terms.
5. **Dedicated Hosts** :arrow_right: A dedicated host is a physical EC2 server dedicated for your use, you can purchase On-Demand on hourly.

##### Instances Types:
- General Purpose.
- Compute Optimized.
-	Memory-Optimized.
-	Accelerated Computing.
-	Storage Optimized.

Note: [Clik here for indepth of instance type](https://aws.amazon.com/ec2/instance-types/)

##### What determines the EC2 price?
- Clock Hours of Server Time.
- Instance Type.
- Auto Scaling.
- Number of Instances.
- Pricing Model.


##### How to launch an Amazon EC2:
1. [Steps to Launch an Amazon EC2](https://aws.amazon.com/premiumsupport/knowledge-center/free-tier-windows-instance/)
2. [Demo video for Launch an Amazon EC2](https://www.youtube.com/watch?v=wcy0ktHDnT4)

##### Reference Link for more info:
[Official Document Link for EC2](https://docs.aws.amazon.com/ec2/index.html)

## 2. Amazon s3
S3 is an object storage built to store and retrieve any amount of data from anywhere on the Internet.  It's a simple storage service that offers industry-leading durability, availability, performance, security, and virtually unlimited scalability at a very low cost.

- Amazon S3 objects can range in size from 0 bytes to a maximum of 5TB.
- S3 object tags are key-value pairs.
- The largest object that can be uploaded in a single PUT is 5 GB.
- Amazon S3 is designed for 99.999999999% (11 9's) of durability.
- Amazon S3 offers a Service Level Agreement (SLA).
- You can pay for storing objects in your S3 buckets and how long you store the objects.
- Data transfer into S3 is free but Data transfer out from S3 is pricing depending upon regions.
- S3 is a universal namespace and S3 has unlimited storage.

##### S3 Storage Classes:
1. S3 Standard (general-purpose storage of frequently accessed data).
2. S3 Intelligent - Tier (data with unknown or changing access patterns).
3. S3 Standard - Infrequent Access (for long-lived).
4. S3 One Zone - Infrequent Access (for long-lived)
5. S3 Glacier (for long term archive and digital preservation).
6. S3 Glacier Deep Archive (for long term archive and digital preservation)
![image](https://user-images.githubusercontent.com/101859396/158961657-6d33c286-f02e-430c-a922-c9249e7c0f1a.png)

##### Charged for the S3 in the following ways:
1. Storage Class.
2. No.of Requests.
3. Storage Management Pricing.
4. Data Transfer Pricing.
5. Transfer Acceleration.
6. Cross-Region Replication Pricing.

##### How to launch an Amazon S3:
1. [Steps to Create a Amazon S3 bucket](https://docs.aws.amazon.com/AmazonS3/latest/userguide/creating-bucket.html)
2. [Demo video for create a Amazon S3 bucket](https://www.youtube.com/watch?v=e6w9LwZJFIA)

##### Reference Link for more info:
[Official Document Link for Amazon S3](https://aws.amazon.com/s3/?did=ft_card&trk=ft_card)


## 3. Amazon RDS
Amazon RDS makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while managing time-consuming database administration tasks, freeing you to focus on your applications and business.

- Amazon RDS supports the following engines.
	- MySQL
	- MariaDB
	- PostgresSQL
	- Oracle
	- Microsoft SQL Server
- These DB engines enable you to create Read replicas in Amazon RDS.
- Amazon RDS supports Multi-AZ deployment.

##### Amazon RDS Instances Types:
- Amazon RDS DB Instances can be provisioned with either 
	- General Purpose (SSD)
	- Provisioned IOPS (SSD)
	- standard (magnetic) storage. 
- Provisioned IOPS is a storage option designed to deliver fast, predictable, and consistent I/O performance, and is optimized for I/O-intensive, transactional (OLTP) database workloads.

##### What determines the RDS price?
- DB instances hour.
- Storage (per GB per month).
- I/O requests per month.
- Backup storage.
- Data Transfer.
- 
##### How to Create a Amazon RDS:
1. [Steps to Create a Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_CreateDBInstance.html)
2. [Demo video for create a Amazon RDS](https://www.youtube.com/watch?v=knrNBkr5iTM)

##### Reference Link for more info:
[Official Document Link for Amazon RDS](https://docs.aws.amazon.com/rds/index.html)


## 4. Amazon EC2 Auto Scaling
Amazon EC2 Auto Scaling helps increase or decrease the EC2 instance to handle the load for your application.

- In Auto Scaling group you can specify the minimum no.of instances and maximum no.of instances in each Auto Scaling group. Then Amazon EC2 autoscaling never cross those limits of instances.
- Amazon EC2 Auto Scaling manages the launch and termination of these EC2 instances on your behalf by define a set of criteria.
- Adding Auto Scaling groups to your network architecture helps make your application more highly available and fault tolerant.
- An Auto Scaling group can contain EC2 instances in one or more Availability Zones within the same Region. However, Auto Scaling groups cannot span multiple Regions.

##### How to Create a Amazon EC2 Auto Scaling:
1. [Steps to Create a Amazon EC2 Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/GettingStartedTutorial.html#gs-create-lt)
2. [Demo video for create a Amazon EC2 Auto Scaling](https://www.youtube.com/watch?v=KNzxuANCtdY)

##### Reference Link for more info:
[Amazon EC2 Auto Scaling](https://docs.aws.amazon.com/autoscaling/#amazon-ec2-auto-scaling)
