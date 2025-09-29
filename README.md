# Task 5 – Capture and Analyze Network Traffic using Wireshark

## Objective
Capture live network packets using Wireshark, analyze them, and identify commonly used protocols.

## Tools Used
- Wireshark (free packet capture tool)

## Steps Performed
1. Installed and launched Wireshark.
2. Selected the active network interface and started capture.
3. Browsed websites to generate traffic.
4. Stopped capture after ~1 minute.
5. Applied filters (`http`, `tcp`) to view specific traffic.

## Protocols Identified
- **HTTP (Hypertext Transfer Protocol):**
  - Seen in GET/HEAD requests and responses.
  - Used for web browsing communication.
- **OCSP (Online Certificate Status Protocol):**
  - Used to validate SSL/TLS certificates.
- **TCP (Transmission Control Protocol):**
  - Transport protocol ensuring reliable communication.

## Findings
- Traffic capture showed multiple protocols during browsing.
- HTTP and OCSP packets confirmed secure web communication.
- TCP was observed as the transport protocol.

## Conclusion
The exercise improved my packet analysis skills and protocol awareness using Wireshark.
