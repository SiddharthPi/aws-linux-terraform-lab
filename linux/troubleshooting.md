# Linux Troubleshooting

## Service Management

```bash
systemctl status nginx
systemctl start nginx
systemctl stop nginx

iUsed to check and manage services.

Logs
journalctl -xe

Used to investigate system and service logs.

Processes
top
ps aux

Used to investigate CPU usage and running processes.

Memory
free -m

Used to inspect memory usage.

Disk
df -h

Used to inspect filesystem usage.

Network
ss -tulpn

Used to identify listening ports and associated processes.

Web Troubleshooting
curl localhost

Used to test whether the local web service is responding.


Save it.

---
