# Nmap Open Ports Lab

## Objective

Discover open ports, identify services, detect OS information, and analyze attack surface using Nmap.

## Environment

- Kali Linux (Attacker)
- Metasploitable 2 (Target)

## Step 1 — Verify Connectivity

ping -c 4 <Target-IP>

## Step 2 — Basic Scan

nmap <Target-IP>

## Step 3 — Service Detection

nmap -sV <Target-IP>

## Step 4 — OS Detection

nmap -O <Target-IP>

## Step 5 — Aggressive Scan

nmap -A <Target-IP>

## Analysis Questions

- Which ports are open?
- Which services are running?
- Which OS is detected?
- What risks exist?
- How to reduce attack surface?

## Security Recommendations

- Disable unused ports
- Update services
- Use firewall
- Restrict access

## Tools Used

- Kali Linux
- Metasploitable 2
- Nmap
