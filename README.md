# Pack-Sniff : Network Packet Sniffer

## Overview

This is a lightweight, high-performance network packet capture and analysis tool written in C, designed to intercept, examine network traffic, and support real time packet filtering for sniffing purposes and many more to come...

## Project Status: Work in Progress

**Current State:** The project is undergoing continuous improvements and refinement.

## Features

- Live network interface concurrent packet capture
- Support for multiple network protocols (TCP, UDP, ICMP)
- Configurable packet filtering
- packet information such as destination, source ip address and timestamp  
- Hex representation of packet payload 

## Prerequisites

- libpcap development libraries
- GCC compiler with C11 support
- Linux OS
- GNU Make version 4.3  

## Dependencies

- libpcap
- Standard C libraries

## Installation 

Clone the repository : 
``
git clone https://github.com/ChrinovicMu/Pack-Sniff.git 
``

Navigate to Directory
```
cd Pack-Sniff
```


## Compilation

```bash
make build 
```

## Usage
Will require root privileges 

```bash
make run PF=<protocol>

//EXAMPLE 
make run PF="tcp" or for ipv6 = "ip6 tcp"
```
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[To be determined ]

## Disclaimer

This tool is for educational and network diagnostic purposes. Always ensure you have proper authorization before capturing network traffic.
