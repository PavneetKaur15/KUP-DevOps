# AWS Session- Questions/Answers

# Q1. What is diff b/w cloud computing and on-prem data centers?
Solu- The difference between on-premise and cloud is essentially where your hardware, application and software reside. On-premise means that a company keeps all         of this IT infrastructure onsite, which is either managed by themselves or a third-party. With the Cloud it means that it is housed offsite with someone           else responsible for monitoring and maintaining it.
      Cloud Computing- Advantages
			                 -is easily accessible at anytime and from anywhere, 
			                 -is less expensive and affordable
			                 -is scalable and secure
		                 	 Disadvantages
			                 -requires a relaible and continuous internet connection
      On-prem- Advantages
		           -complete control over the hardware and software platforms
		           -one does not has to rely on the internet connectivity to access the software
		           Disadvantages
		           -maintaining and updating systems	
		           -is costly as large upfront expenditure and maintenance costs
		           -responsibility for maintaining server hardware and software.

# Q2. Types of cloud computing?
Solu- The following are the types of cloud computings:
      - Public Clouds
  	    These type of cloud environments are not owned by the end user and the computing resources are managed and operated by the Cloud Service Provider. It is open to all to store and access information via the internet using the pay-per-usage method. 
      - Private Clouds
	      This cloud environment is dedicated to a single end user or group. It is used by 	organizations to build and manage their own data centers internally or           third party.
      - Hybrid Clouds
	      This type of cloud is a combination of public and private cloud. This is partially 	secure because the services running on the public cloud can be                 accessed by anyone, while services on private cloud remain to the organisation’s user only.   

# Q3. Difference b/w roles and user in AWS?
Solu- 
User- An IAM user is an entity that you create in AWS. The IAM user represents the person or service who uses the IAM user to interact with AWS. A user in AWS           consists of a name, a password to sign into the AWS Management Console. When you create an IAM user, you grant it permissions by making it a member of a           user group that has appropriate permission policies attached, or by directly attaching policies to the user.

Role- An IAM role is very similar to a user, in that it is an identity with permission policies that determine what the identity can and cannot do in AWS.               However, a role does not have any credentials associated with it. Instead of being uniquely associated with one person, a role is intended to be assumable         by anyone who needs it. An IAM user can assume a role to temporarily take on different permissions for a specific task. 


# Q4. What is CIDR Block?
Solu- Classless Inter-Domain Routing (CIDR) block basically is a method for allocating IP addresses and IP routing. In case of AWS, p is a number from 16 to 28.         It represents the number of bits that are inherited from given IP address. E.g., 10.0.0.0/16 represents an IP address.

# Q5. What is NAT Gateway?
Solu- A NAT gateway is a Network Address Translation (NAT) service. You can use a NAT gateway so that instances in a private subnet can connect to services             outside your VPC but external services cannot initiate a connection with those instances.

# Q6. Why do we need VPC Peering?
Solu- A Virtual Private Cloud (VPC) is a logically isolated, virtual network within a cloud provider. A VPC peering connection is a networking connection between       two VPCs that enables you to route traffic between them using private IP addresses. VPC peering allows you to deploy cloud resources in a virtual network         that you have defined. Instances in either VPC can communicate with each other as if they were within the same network. Data can be transferred across these       resources with more security.

# Q7. What is difference between Internet Gateway and NAT Gateway?
Solu- 
Internet Gateway- An Internet Gateway (IGW) is a logical connection between an Amazon VPC and the Internet. Only one can be associated with each VPC. If a 		                       VPC does not have an Internet Gateway, then the resources in the VPC cannot be accessed from the Internet. An Internet Gateway allows resources                   within your VPC to access the internet, and vice versa. In order for this to happen, there needs to be a routing table entry allowing a subnet                     to access the IGW.
NAT Gateway- A NAT Gateway allows resources in a private subnet to access the internet. It only works one way. The internet at large cannot get through 	  		                your NAT to your private resources unless you explicitly allow it.




