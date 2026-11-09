# Case Study 2: Network Connectivity and DNS Troubleshooting

**Ticket:** #424789  
**Organization:** Omerhi Technologies (fictional)  
**Department:** Network Support  
**Assigned Technician:** Alex Morgan (simulated agent)  
**Priority:** High  
**Status:** Closed

## Incident Overview

A simulated employee, Michael Thompson from the Operations Department, reported being unable to access websites and cloud-based applications from his Windows workstation.

Other employees appeared to have working internet connections, suggesting a workstation-specific problem.

## Troubleshooting Objectives

- Verify network adapter configuration.
- Test connectivity to the default gateway.
- Test external internet connectivity.
- Investigate DNS resolution.
- Verify HTTPS connectivity.
- Document findings and corrective actions.

## Hands-On Network Diagnostics

The following tests were performed on a separate Windows lab workstation, not the fictional employee's device.

| Command | Result |
|---|---|
| `ipconfig /all` | Verified IPv4 address, subnet mask, default gateway, DHCP, and DNS configuration |
| `ping 192.168.1.254` | Successful; 0% packet loss, 7 ms average latency |
| `ping 8.8.8.8` | Successful; 0% packet loss, 23 ms average latency |
| `nslookup google.com` | Successfully resolved IPv4 and IPv6 addresses |
| `Test-NetConnection google.com -Port 443` | TCP connectivity succeeded |
| `ipconfig /flushdns` | DNS resolver cache successfully cleared |
| `Get-DnsClientServerAddress` | Inspected configured IPv4 and IPv6 DNS servers |

## Diagnostic Findings

The local workstation tests confirmed that:

1. The workstation had a valid network configuration.
2. The default gateway was reachable.
3. External IP connectivity was operational.
4. DNS resolution was working.
5. HTTPS connectivity on TCP port 443 was successful.

No network connectivity failure was identified on the actual lab workstation.

## Simulated Root Cause

For the fictional support ticket, an incorrect DNS server configuration was selected as the simulated root cause.

This scenario demonstrated how DNS configuration problems can prevent websites from loading even when basic IP connectivity is working.

## Simulated Resolution

The fictional incident was resolved by:

1. Identifying the incorrect DNS server configuration.
2. Restoring the approved DNS settings.
3. Clearing the DNS resolver cache.
4. Retesting domain name resolution.
5. Verifying website accessibility.
6. Documenting the resolution and closing the ticket.

These corrective actions and verification results were simulated; no DNS configuration was changed on the fictional employee's device.

## Skills Demonstrated

- TCP/IP fundamentals
- Windows network troubleshooting
- DHCP and DNS configuration analysis
- ICMP connectivity testing
- PowerShell network diagnostics
- Incident documentation
- Root cause analysis
- Ticket resolution and closure

## Training Disclaimer

This case study combines real diagnostic commands executed on a local Windows workstation with a separately simulated help desk incident. The fictional employee's network was not accessed or modified.
