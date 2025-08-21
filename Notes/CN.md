# Computer Networks (CN) Notes

## 1. Introduction
- Computer Network = collection of interconnected devices that communicate.
- Goals: resource sharing, communication, reliability, scalability.

## 2. Network Topologies
- **Bus** → Single backbone, easy but failure affects whole.
- **Star** → Central hub, easy to manage, but hub failure = network down.
- **Ring** → Each node connected in a loop, failure breaks network.
- **Mesh** → Every node connected, very reliable, expensive.
- **Hybrid** → Mix of topologies.

## 3. OSI Model (7 Layers)
1. **Physical** – Transmission of raw bits (cables, signals).
2. **Data Link** – Error detection/correction, MAC addressing.
3. **Network** – Routing, IP addressing.
4. **Transport** – Reliable delivery (TCP, UDP).
5. **Session** – Establish, manage, terminate sessions.
6. **Presentation** – Data format, encryption, compression.
7. **Application** – User interface (HTTP, FTP, SMTP).

## 4. TCP/IP Model (4 Layers)
1. Network Interface
2. Internet (IP)
3. Transport (TCP/UDP)
4. Application (HTTP, FTP, DNS)

## 5. Transmission Media
- **Wired** → Coaxial, Twisted Pair, Optical Fiber.
- **Wireless** → Radio waves, Microwaves, Infrared.

## 6. Network Devices
- Hub (broadcasts data), Switch (filters, forwards), Router (routes between networks), Gateway, Modem, Access Point.

## 7. IP Addressing
- IPv4: 32-bit (e.g., 192.168.1.1).
- IPv6: 128-bit (e.g., 2001:db8::1).
- Subnetting used to divide networks.

## 8. Protocols
- **Application Layer**: HTTP, FTP, SMTP, DNS.
- **Transport Layer**: TCP, UDP.
- **Network Layer**: IP, ICMP, ARP.

## 9. Network Security
- Threats: Eavesdropping, Spoofing, DoS.
- Solutions: Firewalls, Encryption, VPN, IDS/IPS.
