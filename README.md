## ARP Spoofer

A Python script that performs an ARP spoofing attack to redirect the flow of network packets, allowing interception of data.

### Features

- Spoof ARP responses to redirect network traffic
- Restore ARP tables to their original state after interruption

### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Daniel-Ikenna/arp_spoof
   ```

2. **Configure Target and Gateway IP**:
   Edit the script to set the `target_ip` and `gateway_ip` variables.

3. **Run the Script**:
   ```bash
   sudo python arp_spoof.py
   ```
4. **Enable port forwarding**:
   Open a new tab and run the command
   ```bash
   echo 1 > /proc/sys/net/ipv4/ip_forward
   ```

### Requirements

- Python 3.x
- `scapy` library (install via `pip install scapy`)
- Superuser privileges (use `sudo`)

### Important Note

This script is intended for educational purposes only. Ensure you have permission before running it on any network.

### Authors

- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
