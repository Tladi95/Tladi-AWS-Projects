# Tladi AWS Projects

## Design and Deploy a Secure AWS VPC Infrastructure

### Architecture Diagrams and Configuration Screenshots

#### Architecture diagram
![AWS Architecture](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/AWS-ARCHITECTURE.jpg)

#### VPC Dashboard: Confirming the custom VPC name and the 10.0.0.0/16 
CIDR block. 
![VPC](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/VPC.PNG)

### Subnets & Route Tables: Confirming explicit route table associations 
for both the public and private subnets. 

#### Public Subnet Configuration
![Public Subnet](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/public-subnet.PNG)

![Public Subnet Route Table](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/public-subnet-rt.PNG)

#### Private Subnet Configuration
![Private Subnet](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/private-subnet1.PNG)

![Private Subnet Route Table](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/Private-subnet-rt.PNG)

#### Gateways: Confirming the active, available status of both the NAT 
Gateway and Internet Gateway.  

#### Internet Gateway
![Internet Gateway](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/igw.PNG)

#### NAT Gateway
![NAT Gateway](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/nat-gateway.PNG)

#### Security group and Network ACLs

#### Network ACL Configuration
![Network ACL Inbound](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/NetworkACL-inbond.PNG)

![Network ACL Outbound](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/NetworkACL-out.PNG)

#### Public Security Group Settings
![Public Security Group Inbound Rules](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/public-sg-inbound-settings.PNG)

![Public Security Group Outbound Rules](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/public-sg-outbound-settings.PNG)

#### Private Security Group Settings
![Private Security Group Inbound Rules](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/private-sg-inbound-settings.PNG)

![Private Security Group Outbound Rules](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/private-sg-outbound-settings.PNG)

#### Connectivity Verification Theory

#### Public internet access
![Public Instance Internet Access](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/public-instance-internet-access.PNG)

#### Private internet access
![Private Instance Internet Access](Design%20and%20Deploy%20a%20Secure%20AWS%20VPC%20Infrastructure/private-instace-internet-access.PNG)
