# Networking Basics #1

This project contains Bash scripts that demonstrate fundamental networking concepts and commands.

## Learning Objectives

- Understanding localhost/127.0.0.1
- Understanding 0.0.0.0
- Working with /etc/hosts file
- Displaying active network interfaces
- Using netcat for network connections

## Requirements

- Ubuntu 22.04
- All scripts must be executable
- All scripts must pass Shellcheck (version 0.7.0)
- First line: `#!/usr/bin/env bash`
- Second line: Comment explaining the script

## Tasks

### 0. Change your home IP
**File:** `0-change_your_home_IP`

Bash script that configures an Ubuntu server with custom DNS mappings:
- localhost resolves to 127.0.0.2
- facebook.com resolves to 8.8.8.8

### 1. Show attached IPs
**File:** `1-show_attached_IPs`

Bash script that displays all active IPv4 IPs on the machine.

### 2. Port listening on localhost
**File:** `2-port_listening_on_localhost`

Bash script that listens on port 98 on localhost using netcat.

## Author

Holberton School Project
