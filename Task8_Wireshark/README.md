# Task 8 - Capture Network Traffic with Wireshark

## Objective

Capture and analyze network traffic using Wireshark.

## Tools Used

- Wireshark
- Windows 11

## Steps Performed

1. Opened Wireshark.
2. Selected the active Wi-Fi interface.
3. Captured live network traffic.
4. Generated traffic by browsing websites.
5. Applied DNS and TLS display filters.
6. Analyzed captured packets.
7. Saved the packet capture.

## Filters Used

### DNS

```
dns
```

Displays Domain Name System queries and responses.

### TLS

```
tls
```

Displays encrypted HTTPS traffic.

## Observations

- DNS packets resolved website domain names.
- Most web traffic was encrypted using TLS.
- HTTP traffic was not visible because modern websites use HTTPS.

## Files Included

- wireshark_capture.pcap
- Screenshots
- README.md

## Conclusion

This task demonstrated how to capture, filter, and analyze live network traffic using Wireshark. DNS and TLS packets were successfully identified and examined.
