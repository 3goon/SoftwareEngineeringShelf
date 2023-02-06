# AWS Networking Definitions

## Basic definitions
- **IP Address**: An IP address is a unique address that identifies a device on the internet or a local network. Just like each home has a mail address, each computer has an IP address. It's a 32-bit, which means it has 32 zero and one.
- **IPv4**:  It's a decimal format IP address that is separated by a period.
- **CIDR Notation**: CIDR notation is a compressed way of specifying a range of IP addresses. 

## AWS Definitions
- **VPC**:  Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. 

## Nice to remember
- `CIDR` stand for : Classless Inter-Domain Routing
- `CIDR` notation contains a `/` forward by a number that the number demonstrate a fix part of the IP.
	- EX : 192.168.1.0/16 provides 65,536 IPs.
- When creating a `VPC` in `aws` we use `CIDR` notation.

## Resources
- [Introduction to Computer Networking](https://web.stanford.edu/class/cs101/network-1-introduction.html)
- [CIDR - Classless Inter-Domain Routing](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing)