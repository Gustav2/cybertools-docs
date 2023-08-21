---
layout: default
title: Nmap
parent: Networking
---

# Nmap

## Target

| Name         | Switch   | Format           | Example                      | Notes                        |
|--------------|----------|------------------|------------------------------|------------------------------|
| Single IP    |          | nmap <ip>        | nmap 192.168.1.1             |                              |
| Multiple     |          | nmap <ip> <ip>   | nmap 192.168.1.1 192.168.1.2 |                              |
| Range        |          | nmap <ip>-<ip>   | nmap 192.168.1.1-255         |                              |
| CIDR         |          | nmap <ip>/<cidr> | nmap 192.168.1.0/24          |                              |
| Domain       |          | nmap <domain>    | nmap google.com              |                              |
| Target file  | -iL      | nmap -iL <file>  | nmap -iL targets.txt         |                              |
| Random hosts | -iR      | nmap -iR <num>   | nmap -iR 100                 | Num is amount of targets     |
| Exclude host | -exclude | -exclude <ip>    |                              | Only used with other targets |

