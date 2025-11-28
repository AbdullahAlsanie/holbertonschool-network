# Networking Basics #0

This project covers fundamental networking concepts including the OSI model, network types, protocols, and basic network diagnostic tools.

## Learning Objectives

By completing this project, you will be able to explain:

### OSI Model
- What the OSI model is
- How many layers it has
- How it is organized

### Network Types
- What is a LAN (Local Area Network)
- Typical LAN usage and geographical size
- What is a WAN (Wide Area Network)
- Typical WAN usage and geographical size
- What is the Internet

### IP Addressing
- What is an IP address
- The 2 types of IP addresses (IPv4 and IPv6)
- What is localhost
- What is a subnet
- Why IPv6 was created

### TCP/UDP
- The 2 main data transfer protocols for IP
- Main difference between TCP and UDP
- What is a port
- SSH (22), HTTP (80), and HTTPS (443) port numbers
- Tools/protocols used to check network connectivity

## Requirements

### Bash Scripts
- Allowed editors: vi, vim, emacs
- Interpreted on Ubuntu 22.04
- All files end with a new line
- All bash scripts are executable
- First line: `#!/usr/bin/env bash`
- Second line: Comment explaining the script's purpose
- Scripts must pass shellcheck without errors

### Answer Files
- Each answer on a new line
- Numeric answers for multiple choice questions

## Tasks

### 0. OSI model
**File:** `0-OSI_model`

Multiple choice questions about the OSI model concept and organization.

### 1. Types of network
**File:** `1-types_of_network`

Questions about LAN, WAN, and Internet network types.

### 2. MAC and IP address
**File:** `2-MAC_and_IP_address`

Questions about MAC and IP address definitions.

### 3. UDP and TCP
**File:** `3-UDP_and_TCP`

Questions about TCP and UDP protocol characteristics.

### 4. TCP and UDP ports
**File:** `4-TCP_and_UDP_ports`

Bash script that displays listening ports with PID and program names.

**Usage:** `sudo ./4-TCP_and_UDP_ports`

### 5. Is the host on the network
**File:** `5-is_the_host_on_the_network`

Bash script that pings an IP address 5 times.

**Usage:** `./5-is_the_host_on_the_network {IP_ADDRESS}`

## Author

Holberton School Project
