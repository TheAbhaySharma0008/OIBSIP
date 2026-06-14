# Task 1: Basic Network Scanning with Nmap

## Objective
Perform a network scan to identify open ports and services using Nmap.

## Tool Used
- Nmap

## Commands Executed

```bash
nmap --version
```

```bash
nmap 127.0.0.1
```

```bash
nmap 127.0.0.1 -oN nmap_scan_results.txt
```

## Findings

The scan was performed on the local machine (127.0.0.1).

Nmap identified the open ports and services running on the system. Open ports indicate services that are available for network communication.

## Importance

- Helps identify active services.
- Assists in security auditing.
- Detects unnecessary exposed ports.
- Improves overall system security.

## Conclusion

Nmap successfully scanned the local system and provided information about available network services and open ports.
