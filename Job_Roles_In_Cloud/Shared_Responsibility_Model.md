# Shared Responsibility Model

Security and compliance are a shared responsibility between AWS and the customer. 
This shared model can help reduce the customer's operational burden as AWS operates, manages and controls the host operating system components and the virtualization layer, right down to the physical security of the premises in which the service operates. 

Customers should carefully examine the services they choose, as their respective responsibilities vary according to the services used; the integration of these services into their IT environment and applicable laws and regulations. 

The nature of these shared responsibilities also provides the flexibility and customer control needed for deployment. As can be seen in the graphic below, this distinction between responsibilities is commonly referred to as security “of” the cloud versus security “in” the cloud.

![alt text](SharedResponsibilityModel.png)

## AWS's responsibility: “cloud security”: 
AWS is responsible for protecting the infrastructure that runs all the services offered on the AWS Cloud. This infrastructure is made up of the hardware, software, networks and facilities that run the AWS Cloud Services.

## Customer responsibility: “cloud security”: 
The customer's responsibility will be determined by the AWS Cloud Services selected by them. This determines the number of configuration operations that the customer must perform as part of their security responsibilities.
For example, a service such as Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS) and therefore requires the customer to perform all the necessary configuration and security management tasks.
Customers deploying an Amazon EC2 instance are responsible for managing the guest operating system (which includes updates and security patches), any utilities or application software installed by the customer on the instances, as well as configuring the firewall provided by AWS (called a security group) on each instance.
