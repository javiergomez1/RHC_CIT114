#  Module 10. Databases
## Notes 8: Databases


### 1) Key Points Summarized
- Database - A shared collection of related data used to support the activities of a particular organization.
- AWS RDS - Managed Relational Database Service which includes database engines
  1. MySQL
  2. AWS Aurora
  3. MS SQL
  4. PostgreSQL
  5. MariaDB
  6. Oracle
- AWS DynamoDB
- AWS Redshift
- AWS Aurora 
- SQL
- NoSQL
- Multi-AZ DB Instance


### 2) Two Quotes Identified
- AWS Solutions typically fall into 1 of 2 categories, unmanaged or managed
  1. Unmanaged - Scaling, fault tolerance, and availability ar managed by you
  2. Managed - Scaling, fault tolerance, and availability are typically built in to the service
- Each DB subnet group requires subnets in at least two Availability Zones
  1. Multi-AZ deployments provide enhanced availability and durability for DB instances - Ideal for Production environment
  2. AWS RDS automatically creates Primary & Standby instances in different AZ, when you provision a Multi-AZ DB Instance



### 3) New Facts Learned were Described
- AWS RDS databases can be configured to replicate to other availability zones, then configure an application in an EC2 instance to connect to the replicated database, if the primary database becomes unavailable.
- 
