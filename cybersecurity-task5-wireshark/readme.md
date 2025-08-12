# Task 5: Capture and Analyze Network Traffic using Wireshark (Kali Linux)

## Objective
To capture and analyze network traffic in real-time and identify at least 3 protocols.

## Environment
- OS: Kali Linux
- Tool: Wireshark

## Steps Performed
- Installed Wireshark using `apt`.
- Started Wireshark and captured packets on `wlan0`.
- Generated network traffic using `ping`, `curl`, and Firefox.
- Analyzed packets using filters (`dns`, `http`, `tcp`).

## Protocols Observed
- **DNS**: Domain name lookups.
- **HTTP**: Web page requests.
- **TCP**: Transport layer protocol used by HTTP and DNS.

## Output
- `task5_capture.pcap` [Note: This file can be opened only using Wireshark]

