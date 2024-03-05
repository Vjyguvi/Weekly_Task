# Task: Networking Setup and Configuration
>> Note : Task is related to Router configuration (OSPF and BGP) which does not come under Devops.
## Test Case 1: Configure routing protocols (e.g., OSPF, BGP) on routers to enable dynamic routing.
>> Expected Outcome: Routers should be able to exchange routing information and dynamically update routing tables.
+ Two VPCs have been created and connected using VPC peering. Routes have been added to the route tables.
  + VPC Creation
  >> ![VPC Creation](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/cffa88ea-8cb3-47fc-8ef0-89cdc85f5d33)
  + VPC Peering
  >> ![VPC Peer](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/0cc8e36d-4191-4474-ab7f-b04869fbb8c7)
  + Route Table
  >> ![Routes added](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/4bfe8124-0026-43bc-b4a7-862c5ff13ca7)
## 2. Firewall Rules Setup: Test Case 2: Define and implement firewall rules to restrict incoming and outgoing traffic basedon security policies.
>> Expected Outcome: Traffic should be filtered according to the defined firewall rules, allowing only authorized communication.
+ Firewall configuration is implemented using Network Access Control Lists (NACLs) at the subnet level and Security Groups at the instance level.
  + NACL
  >> ![inbound rules NACL](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/2b3201f9-5663-42b7-af00-a0ed30cbd4e9)
  + Security Groups
  >> ![inbound rules SG](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/2f2c004b-bb0d-4ba7-ab59-3954f0da10f5)
## 3. Load Balancer Configuration: Test Case 3: Configure a load balancer to distribute incoming traffic across multiple servers in a backend pool.
>> Expected Outcome: The load balancer should evenly distribute traffic among the backend servers, ensuring high availability and scalability.
+ Two instances have been provisioned as web servers and added to a target group, which has been configured within the load balancer.
  + Target Group
  >> ![TG Created](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/04354ce6-71c4-4f31-a5c5-f3ac9332c011)
  + Application LoadBalance
  >> ![LB Created](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/422fad94-7671-4426-b524-0c93b545654a)
  + Output LoadBalancer DNS
  >> ![LB S2](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/c4a94bc4-5ada-46f9-9270-c4e1ee92c7b1)
  >> ![LB S1](https://github.com/Vjyguvi/Weekly_Task/assets/150816386/df308dfe-e0c9-44b6-b52a-dd2b142f55c0)
