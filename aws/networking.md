# AWS Networking Lab

## VPC

A Virtual Private Cloud provides an isolated network in AWS.

Example:

10.0.0.0/16

## Subnet

A subnet is a smaller network range inside a VPC.

Example:

10.0.1.0/24

## Internet Gateway

An Internet Gateway provides a path between the VPC and the internet.

## Route Table

A route table controls where network traffic is sent.

Example:

0.0.0.0/0 -> Internet Gateway

## Security Group

A Security Group acts as a virtual firewall controlling allowed traffic.

Example:

- TCP 22 -> SSH
- TCP 80 -> HTTP

## Troubleshooting Lab

I tested connectivity by changing:

- Security Group rules
- Route table configuration
- Internet Gateway configuration
- Public IP availability

The goal was to understand why an otherwise healthy EC2 instance could become unreachable from the internet.
