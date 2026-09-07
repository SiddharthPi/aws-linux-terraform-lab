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
