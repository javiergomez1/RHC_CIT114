# Module 6 
## Notes 4: Cloud Security with DevOps

### 1) Key Points Summarized
- Network ACL - Access Control Lists
- IAM - Identity and Access Management - Main Components:
  1. Users
  2. Services
  3. Applications
- Principle of Least Privilege - By default give users and objects the least permissions possible, and gradually start granting more as needed.
- Securing Data
  1. Data at Rest - Data stored on disks, backup tapes or any other storage device
  2. Data in Transit - Data in route between a source and destination, it is secured by SSL(Secure Sockets Layers) and TLS(Transport Layer Security)
- AWS Networking
  1. Elastic Load Balancing
  2. Amazon VPC - Virtual Private Cloud = Router, Switch, Network pipeline
- AWS Compute
  1. AMI - Amazon Machine Images
  2. EC2 - Elastic Compute Cloud
- AWS Storage & Databases
  1. EBS - Electic Block Store = DAS - Direct Attached Storage
  2. EFS - Electric File System = SAN - Storage Area Network
  3. S3 - Simple Storage System = NAS - Network Attached Storage
  4. RDS - Relational Database Service = RDBMS - Relational DataBase Management System

### 2) Two Quotes Identified
- In Google Data Centers there are six layers of security
  1. Property Boundaries
  2. Secure Perimeter
  3. Building Access
  4. Security Operations Center (SOC)
  5. Data Center Floor
  6. Where disks are erased or destroyed

- Customer can issue and keep their own encryption keys
  

### 3) New Facts Learned were Described
I learned that within AWS Security, are are somethings that the Customer is responsible to keep secure, and other things AWS is.
- Customer security responsibilities include:
  1. Customer Data
  2. Platform, Applications, Identity & Access Management
  3. Operating System, Network & Firewall Configuration
  4. Client-side data encryption & data integrity authentication
  5. Server-side encryption, file system and/or data
  6. Network traffic protection - Encryption, Integrity & Identity

- AWS security responsibilities include:
  1. Software
  2. Compute
  3. Storage
  4. Database
  5. Networking
