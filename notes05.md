# Module 7
## Notes 5: Networking & Content Delivery

### 1) Key Points Summarized
- CDN - Content Delivery Network
- AWS Edge Location - Third party data centers set up to ensure minimal latency.
- AWS CloudFront - Amazon's CDN service, it also uses regional Edge Location cache to minimize latency
- Network ACL - Access Control Lists
- AWS Route 53 - Amazon's registrar & DNS server, a reference to TCP/UDP port 53, where DNS server requests are addressed
- AWS IAM - Identity and Access Management
  1. Principle of Least Privilege - By default give users and objects the least permissions possible, and gradually start granting more as needed.
- AWS CloudTrail - Tracks user activity on an account and keeps logs for 90 days by default.
- Open Systems Interconnection (OSI) Model has 7 Layers
  1. Physical - Transmission and reception of raw bitstreams over a physical medium - Signals (1s and 0s)
  2. Data Link - Transfer data in the same LAN network (hubs & switches) - MAC
  3. Network - Routing and packet forwarding (routers) - IP
  4. Transport - Provides protocols to support host-to-host communication - TCP, UDP
  5. Session - Enables orderly exchange of data - NetBIOS, RPC
  6. Presentation - Ensures that the application layer can read the data; Encryption; - ASCI, ICA
  7. Application - Means for an application to access a computer network - HTTP(S), FTP, DHCP, LDAP

### 2) Two Quotes Identified
- Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. 
- If there is a competition between and Allow statement, and a Deny statement, the Deny statement always wins.
  

### 3) New Facts Learned were Described
- IAM Policies are written in JSON (Java Script Object Notation) scripts
- Amazon recommends to use IAM to create an account with admin rights, and never log in with the root user.
- The smallest size subnet in a VPC is /28
- The maximum size IP address range you can have in a VPC is /16
