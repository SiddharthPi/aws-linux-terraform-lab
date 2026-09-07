AWS Storage

## EBS

Elastic Block Store provides block storage for EC2.

Typical use:

- Operating system disk
- Application data
- Persistent storage

## EFS

Elastic File System provides a shared file system that can be mounted by multiple Linux EC2 instances.

EFS uses NFS.

Typical use:

- Shared application files
- Shared web uploads

## S3

Simple Storage Service is object storage.

Typical use:

- Backups
- Images
- Videos
- Logs
- Static website files

S3 is accessed through APIs, URLs, SDKs, or AWS CLI rather than behaving like a normal mounted Linux filesystem.
