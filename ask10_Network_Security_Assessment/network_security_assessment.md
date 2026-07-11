# Network Security Assessment Report

## Scope

Assessment of the local host using Nmap and Wireshark.

## Methodology

### Port Scanning

Performed using:

```bash
nmap 127.0.0.1
```

### Packet Capture

Captured live traffic while browsing websites.

Filters used:

- dns
- tls

## Findings

### Nmap

- Host reachable.
- No unnecessary open TCP ports detected.

### Wireshark

Observed:

- DNS queries
- TLS encrypted traffic
- Normal client-server communication

## Security Recommendations

- Keep unnecessary services disabled.
- Enable the Windows Firewall.
- Use HTTPS whenever possible.
- Update software regularly.
- Monitor network traffic periodically.

## Conclusion

The assessment demonstrated fundamental network security analysis using both active scanning (Nmap) and passive monitoring (Wireshark). No suspicious activity was identified during testing.
