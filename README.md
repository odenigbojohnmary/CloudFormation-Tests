This template deploys an AutoScaling Group with Application Load Balancer that Scales with Traffic (Web Servers), AutoScaling Group that Scales with Amazon Queue System (Worker Servers), An SFTP Server with a Network LoadBalancer, An Amazon Columnar DataBase(Redshift Server)  with a VPC, with public and private subnets in 2 AZs. It deploys an internet gateway, with a default
  route on the public subnets. It deploys 2 NAT gateways (one in each AZ),
  and default routes for them in the private subnets. It deploys the Web server and the SFTP server across the public subnet, deploy the Worker Server and the Database across the Private Subnet. 
  It also deploys Security Group for each Component which is uses to restrict access the component.
  It also deploys Monitoring and cloud watch matrics with Alarms for proper monitoring.
