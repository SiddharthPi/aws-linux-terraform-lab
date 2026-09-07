# AWS EC2

## What is EC2?

Amazon EC2 provides virtual servers in AWS.

## My Lab

- Ubuntu EC2 instance
- SSH access
- Nginx web server
- Security Group allowing SSH and HTTP

## Troubleshooting Performed

### Website Inaccessible

Checked:

1. EC2 instance state
2. Nginx service
3. Security Group
4. Public IP
5. Route table
6. Internet Gateway

Useful commands:

```bash
systemctl status nginx
ss -tulpn
curl localhost
## Troubleshooting Process

When a website is inaccessible, I check the issue layer by layer:

1. Is the EC2 instance running?
2. Is Nginx running?
3. Is port 80 listening?
4. Does the Security Group allow HTTP?
5. Does the instance have a public IP?
6. Does the subnet route to an Internet Gateway?
