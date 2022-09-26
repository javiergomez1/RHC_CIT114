# Module 7
## Notes 05: Networking & Content Delivery

### 1) Key Points Summarized
- CDN - Content Delivery Network
- AWS Edge Location - Third party data centers set up to ensure minimal latency.
- AWS CloudFront - Amazon's CDN service, it also uses regional Edge Location cache to minimize latency
- Network ACL - Access Control Lists
- AWS Route 53 - Amazon's registrar & DNS server, a reference to TCP/UDP port 53, where DNS server requests are addressed
- AWS IAM - Identity and Access Management
  1. Principle of Least Privilege - By default give users and objects the least permissions possible, and gradually start granting more as needed.
- AWS CloudTrail - Tracks user activity on an account and keeps logs for 90 days by default.

### 2) Two Quotes Identified
- Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. 
- If there is a competition between and Allow statement, and a Deny statement, the Deny statement always wins.
  

### 3) New Facts Learned were Described
- IAM Policies are written in JSON (Java Script Object Notation) scripts
- Amazon recommends to use IAM to create an account with admin rights, and never log in with the root user.
- The smallest size subnet in a VPC is /28
- The maximum size IP address range you can have in a VPC is /16
