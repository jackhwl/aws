## AWS Certified Solutions Architect - Associate (SAA-C03): Fundamental Services
### AWS Fundamentals
  - The Building Blocks of AWS: Availability Zones and Regions
    - A Region: have more AZ
    - An AZ: have more data centers
    - Edge locations: endpoint foor caching content, consist of CloudFront (CDN)
      - A networking point of presence that is one of many spread across the globe that is commonly used to cache content.
  - Who Owns What in the Cloud
    - Can you do this yourself in the AWS Management Console?
      - If yes, you are likely responsible
      - If not, AWS is likely responsible
      - Encryption is a shared responsibility
  - Compute, Storage, Databases, and Networking
    - Compute: EC2, Lambda, Elastic Beanstalk
    - Storage: S3, EBS, EFS, FSx, Storage Gateway
    - Databases: RDS, DynamoDB, Redshift
    - Networking: VPCs, Direct Connect, Route 53, API Gateway, AWS Global Accelerator
  - What is the Well-Architected Framework?
    - https://aws.amazon.com/whitepapers
    - Operational Excellence: runing and monitoring systems to deliver business value, and continually improving processes and procedures
    - Performance Efficiency: using IT and computing resources efficiently
    - Security
    - Cost Optimization
    - Reliability: Ensuring a workload performs its intended function correctly and consistently when it's expected to
    - Sustainability
  - AWS Fundamentals Exam Tips
### Identity and Access Management (IAM)
  - Securing the Root Account 
  - Controlling Users Actions with IAM Policy Documents
    - Assign Permissions using IAM Policy Documents consiting of JSON
  - Permanent IAM Credentials
    - IAM is Universal
    - IAM Federation
    - Identity Federation
    - Users, Groups, Roles
      - new user without group assign no permission to do anything in aws management console, only action is change password
      - Access Key 
      - Identity provider
    - IAM Exam Tips
### Vitual Private Cloud (VPC) Networking
  - VPC Overview
    - a virtual data center in the cloud
    - fully customizable network
    - CIDR.xyz
    - consists of internet gateway, route tables, network access controls lists, subnets, and security groups
    - 1 subnet is always in 1 availablity zone
  - Demo: Provisioning a VPC Part 1
  - Demo: Provisioning a VPC Part 2
  - Using NAT Gateways for Internet Access
  - Protecting Your Resources with Security Groups
  - Controlling Subnet Traffic with Network ACLs
  - Private Communication Using VPC Endpoints
  - Building Solutions across VPCs with Peering
  - Network Privacy with AWS PrivateLink
  - Securing Your Network with VPN CloudHub
  - Connection On-Premises with Direct Connect
  - Simplifying Networks with Transit Gateway
  - 5G Networking with AWS Wavelength
  - VPC Networking Exam Tips
### Elastic Coompute Cloud (EC2)
  - EC2 Overview
    - Pricing Options
      - On-Demand
      - Reserved
      - Spot
      - Dedicated
  - Demo: Launching an EC2 Instance
  - AWS Command Line
  - Using Roles
  - Security Groups and Boostrap Scripts
  - EC2 Metadata and User Data
  - Networking with EC2
  - Optimizing with EC2 Placement Groups
  - Solving Licensing Issues with Dedicated Hosts
  - Timing Workloads with Spot Instances and Spot Fleets
  - Deploying vCenter in AWS with VMware Cloud on AWS
  - Extending AWS Beyond the Cloud with AWS Outposts
  - EC2 Exam Tips
  - EC2 Instance Bootstrapping