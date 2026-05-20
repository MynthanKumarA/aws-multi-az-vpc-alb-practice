**AWS Highly Available Multi-AZ Infrastructure Practice**



**Overview:**



This hands-on AWS practice project focuses on building a highly available and secure cloud infrastructure manually using core AWS networking services.

The main goal of this practical implementation was to understand how real-world AWS networking, routing, security, and load balancing work together beyond theory.





**Architecture Components**

The infrastructure was built using:



1. Custom VPC

2\. Public Subnets across 2 Availability Zones

3\. Private Subnets across 2 Availability Zones

4\. Internet Gateway

5\. NAT Gateway

6\. Route Tables

7\. Security Groups

8\. EC2 Instances

9\. Application Load Balancer (ALB)

10\. Target Groups





**Architecture Flow**



User → Application Load Balancer → Target Group → EC2 Instances



\-> Public Subnets host the ALB and NAT Gateway

\-> Private Subnets host backend EC2 instances

\-> NAT Gateway provides internet access for private resources

\-> ALB distributes traffic across multiple Availability Zones for High Availability



**Features Implemented**



\-> Multi-AZ architecture setup

\-> Public and Private subnet configuration

\-> Internet routing using IGW and NAT Gateway

\-> Security Group configuration and troubleshooting

\-> EC2 User Data automation

\-> Load balancing across multiple EC2 instances

\-> High Availability infrastructure design



**What I Learned**



Through this practical implementation, I gained a better understanding of:



* VPC networking fundamentals
* Public vs Private subnet architecture
* Route Table configurations
* NAT Gateway routing
* Security Group behavior and troubleshooting
* Application Load Balancer traffic distribution
* High Availability architecture concepts



**Challenges \& Troubleshooting**



During this hands-on practice, I faced and resolved several configuration issues, which helped improve my practical understanding of AWS networking and security.



**Issues Faced**



\* Security Group misconfigurations are preventing traffic flow

\* Route Table confusion during NAT Gateway setup

\* Understanding Public vs Private subnet routing

\* ALB target health check troubleshooting

\* Subnet and Availability Zone configuration verification



**Key Learnings from Troubleshooting**



\* Importance of correctly configuring inbound and outbound Security Group rules

\* Understanding how NAT Gateway routing works for private subnets

\* Verifying proper subnet association with Route Tables

\* Importance of health checks in Application Load Balancer

\* Better understanding of end-to-end traffic flow inside AWS infrastructure





**Author**



**Mynthankumar A**

**Aspiring Cloud / DevOps Engineer**



