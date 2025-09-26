Top 20 Nmap Commands (Using IP: 10.0.2.15)

This document explains why each of the top 20 Nmap commands is used. It
focuses on the purpose of each scan and how it helps in network security
and reconnaissance.

1.  Basic Host Discovery: Used to check if a host is up and what ports
    are open. It is the first step before any detailed scanning.

2.  Ping Scan: Helps identify live hosts on the network without scanning
    their ports. Useful for quickly mapping active devices in a network.

3.  Service Version Detection: Finds which service versions are running
    on open ports. Important for vulnerability assessments, as outdated
    services may be exploitable.

4.  OS Detection: Identifies the operating system of the target. This
    helps attackers or defenders understand the target environment and
    plan accordingly.

5.  Aggressive Scan: Combines OS detection, version detection,
    traceroute, and script scanning. Used when a detailed profile of the
    target is needed.

6.  TCP Connect Scan: Performs a full TCP connection to each port.
    Useful when stealth is not a concern or when SYN scan cannot be
    used.

7.  SYN Scan: A fast and stealthy way to check for open ports without
    completing the handshake. Widely used for reconnaissance.

8.  UDP Scan: Discovers open UDP ports, which may host services like
    DNS, DHCP, or SNMP. Important for a complete security assessment.

9.  Fast Scan: Quickly scans the top 100 most common ports. Saves time
    when a quick overview is needed.

10. Specific Port Scan: Targets only selected ports to reduce noise and
    scan time. Useful when you know which services you want to check.

11. Port Range Scan: Scans a custom range of ports. Helps focus on
    specific segments of the port range.

12. Script Scan: Runs default NSE scripts that gather more information
    about vulnerabilities, services, and configurations.

13. Intense Scan with Script + Version: A more detailed scan combining
    script execution and service version detection for comprehensive
    results.

14. Scan Without DNS Resolution: Skips DNS lookups for faster results.
    Useful when scanning many hosts or when DNS resolution is
    unnecessary.

15. Verbose Scan: Displays more detailed progress information during
    scanning. Helps understand what Nmap is doing.

16. Very Verbose Scan: Gives even deeper insight than normal verbose
    output. Good for troubleshooting or educational purposes.

17. Traceroute + Scan: Shows the network path to the host along with
    open port details. Useful for network topology mapping.

18. Save Results to File: Saves the scan results for future reference or
    documentation. Essential for professional reporting.

19. XML Output: Produces structured output for parsing and automation.
    Often used with tools that analyze scan results.

20. Combine Everything (Ultimate Scan): Runs an aggressive scan on all
    ports with optimized timing. Provides the most detailed picture of
    the target host.

