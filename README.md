# Linux System Monitoring & Automation Toolkit

A beginner-friendly DevOps project focused on Linux system monitoring,
network connectivity checks, and automation using Bash scripting.

## Project Objective

The goal of this project is to gradually build a practical DevOps
toolkit while learning Linux, Networking, Bash/Shell Scripting,
Git/GitHub, AWS, Docker, and other DevOps technologies.

## Technologies

- Linux
- Bash / Shell Scripting
- Networking
- Git
- GitHub
- AWS
- Docker
- Kubernetes
- DevOps Fundamentals

## Project Progress

### Stage 1 – Linux System Monitoring

Completed.

The initial stage focuses on basic Linux system health monitoring.

The monitoring script checks information such as:

- System date
- Hostname
- System uptime
- Memory usage
- Disk usage
- System load
- Network information

Script:

```text
scripts/system_health.sh

### Stage 2 – Networking

Completed.

The networking stage focuses on basic network connectivity
and service/port checks.

Implemented tests include:

Internet connectivity using ping
DNS resolution using nslookup
HTTP connectivity using curl
Listening ports using ss
Local port availability using nc

Script:

```text
ping -c 4 8.8.8.8
nslookup google.com
curl -I https://example.com
ss -tuln
nc -zv 127.0.0.1 80
