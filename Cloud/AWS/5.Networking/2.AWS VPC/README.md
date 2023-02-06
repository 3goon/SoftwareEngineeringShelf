# AWS VPC

## Definitions
- **VPC**:  Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. 
- **VPC Creating settings**: `Region` and `IP range` in CIDR notaion.
- **Subnets**: Smaller networks inside your base network—or virtual area networks (VLANs) in a traditional, on-premises network. 
- **Internet Gateway** or **IGW***: Just as a modem connects your computer to the internet, the internet gateway connects your VPC to the internet.
- **Virtual gateway** or **VGW**: allows you to connect your AWS VPC to another private network.

## Nice to remember
- Each `VPC` could created over several [`Availability Zones`](../../1.Basics/README.md)(`AZ`).
- `aws` reserve 5 ip address of each subnet for `routing`, `DNS` and `network management`.
- Suggested `CIDR` size for __VPC__ is `/16`.
- Suggested `CIDR` size for __Subnet__ is `/24`.
- `VGW` stablished over a encrypted `VPN` connection.

## Resources
- [AWS VPC And Subnets](https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html)
- [AWS Public and Private subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Scenario2.html)