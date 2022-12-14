# Module 6 
## Notes 4: Cloud Security with DevOps

### 1) Key Points Summarized
- Encryption - Encoded data with a secret key, which makes it unreadable
- TLS - Transport Layer Security - Formerly SSL (Secure Socket Layer), is an open standard protocol
- ACL - Access Control Lists 
- AWS KMS - Key Management Service
- AWS Route 53 - Amazon's registrar & DNS server, a reference to TCP/UDP port 53, where DNS server requests are addressed
- AWS IAM - Identity and Access Management
  1. Principle of Least Privilege - By default give users and objects the least permissions possible, and gradually start granting more as needed.
- AWS CloudTrail - Tracks user activity on an account and keeps logs for 90 days by default.
- AWS Shield 
  1. Distributed Denial of Service (DDoS) protection service
  2. Safeguards application on AWS
  3. Always-on detection & automatic inline mitigations
  4. AWS Shield Standard is free, but AWS Shield Advanced is a paid service
  5. To Contact DDoS response team, either Business or Enterprise Support is required
- AWS Trusted Advisor - provides recommendations that help you follow AWS best practices. Trusted Advisor evaluates your account by using checks. These checks identify ways to optimize your AWS infrastructure, improve security and performance, reduce costs, and monitor service quotas.
- AWS Storage Gateway - A hybrid cloud storage service that provides on-premise access to AWS cloud storage.
- AWS S3 Block Public Access - Overides any other policy or object permission. Enabled by default.
- AWS Trusted Advisor - Bucket permission check. Free feature.
- AWS Config - Access, audit, and evaluate the configurations of AWS resources. You can automate the evaluation of recorded configurations.
- AWS Artifact - A resource for compliance-related information. Provides access to security and compliance reports, and select online agreements.
### 2) Two Quotes Identified
- An IAM Group is used to grant the same permissions to multiple users
- Customer can issue and keep their own encryption keys
- ACLs are less commonly used because they predate IAM
  

### 3) New Facts Learned were Described
- IAM Policies are written in JSON (Java Script Object Notation) scripts
- AWS security responsibilities include:
  1. Software
  2. Compute
  3. Storage
  4. Database
  5. Networking
