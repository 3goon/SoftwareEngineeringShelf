# AWS VPC Routing

## Definitions
- **Route**: Each route in a table specifies a destination and a target. 
- **Main Route Table**: The route table that automatically comes with your VPC. It controls the routing for all subnets that are not explicitly associated with any other route table.
- **Custom Route Table**: A route table that you create for your VPC.
- **Network ACL**: A network access control list (ACL) allows or denies specific inbound or outbound traffic at the subnet level. 
- **Security Group**: A security group controls the traffic that is allowed to reach and leave the resources that it is associated with.
   
## Nice to remember
- `0.0.0.0/0`  represents all IPv4 addresses.
- `::/0` represents all IPv6 addresses.
- In `Network ACL` everything is allowed by default.
- In `Security Groups` income traffic is blocked by default.
- A `security group` name must be __unique__ within the `VPC`.
- A `security group` name cannot start with `sg-`.
- `Security groups` are stateful.
- Authorize only specific `IAM` principals to create and modify `security groups`.
- Consider creating `network ACLs` with rules similar to your `security groups`, to add an additional layer of security to your VPC.
- 

## Resources
- [AWS Route tables](https://docs.aws.amazon.com/vpc/latest/userguide/route-table-options.html)
- [AWS VPC Network ACL](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html)
- [AWS VPC Security Group](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)