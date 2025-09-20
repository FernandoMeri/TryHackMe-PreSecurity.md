# Day 1 - [2025/09/02]
## Day 1: 2025-09-02
### Module: Introduction to Cybersecurity
- **I learned**: The difference between Red Team (attackers) and Blue Team (defenders), and why both are crucial.
- **Tools**: None yet, just conceptual theory.
- **Next step**: Module “How the Web Works.”

# Day 2 - [2025/09/18]
## Day 2: 2025-09-18
### Module: Network Fundamentals
- **I learned**: IP addresses and subnets. Basic network tools: `ping`, `traceroute`, `ipconfig`. How routing and DNS work. .
- **Tools**: None yet, just conceptual theory.
- **Next step**: Module “Intro to LAN.”

# Day 3 - [2025/09/19]
## Day 3: 2025-09-19
### Module: Intro to LAN
 **I learned**: 
  - How local networks are segmented using subnets.
  - The difference between public and private IP addresses.
  - How devices find each other on a LAN (ARP).
- **Commands/uses:** 
  - Using `ipconfig`/`ifconfig` to view my IP on the network.
  - Concepts of `ping` to verify connectivity on the LAN.
- **Next step**: Module “OSI Model.”

## Day 3 - [2025/09/19]
### Module: OSI Model
- **I learned**:
- The 7 layers: Physical, Link, Network, Transport, Session, Presentation, Application.
- **Reflection**: 
  - The module reflects the basis for understanding how data travels and how it is attacked.
- **Next step**: Module “Packets & Frames”.

## Day 3 - [2025/09/19]
### Module: Packets & Frames
- **I learned**: 
  - Differences between frames (Ethernet, layer 2) and packets (IP, layer 3).
  - How TCP's Three-Way Handshake works (SYN, SYN/ACK, ACK).
  - Characteristics of UDP (connectionless, faster but less reliable).
  - Practice with common ports and services (e.g., 80=HTTP, 53=DNS).
- **Application in cybersecurity**:
  - Basis for traffic analysis with Wireshark.
  - Port scanning with tools such as Nmap.
- **Next step**: Module "Extending your netwrok"

## Day 3 - [2025/09/19]
### Module: Extending Your Network
- **I learned**:
  - **Port forwarding**: How to redirect external traffic to internal devices.
  - **Firewalls**: How they filter traffic based on rules (e.g., blocking ports).
  - **VPNs**: How to create secure tunnels for remote access.
  - **LAN devices**: Routers, switches, and their roles in the network.
- **Application in pentesting**:
  - Bypassing firewalls and using port forwarding to access internal systems.
  - Auditing VPN configurations in corporate environments.
 
## Day 3 - [2025/09/19]
### Module: DNS in Detail
- **I learned**: 
  - How DNS resolution works and the types of records (A, AAAA, MX, CNAME).
  - The DNS hierarchy: root servers, TLDs, authoritative servers.
  - Tools: `dig`, `nslookup`.
- **Application in pentesting**:
  - Recognition of subdomains and services.
  - Poisoning attacks and data exfiltration via DNS.
 
## Day 4 - [2025/09/20]
### Module: HTTP in Detail
- **I learned**:
  - HTTP methods (GET, POST, PUT, DELETE) and their use.
  - Status codes (200, 404, 302, 500) and their meaning.
  - Common headers (Cookies, User-Agent, Location) and how they affect security.
  - The importance of HTTPS and TLS encryption.
- **Application in pentesting**:
  - Manipulating headers to bypass authentication.
  - Analyzing requests to find vulnerabilities (e.g., IDOR, CSRF).
 
## Day 4 - [2025/09/20]
### Module: How Websites Work
- **I learned**:  
  - How a website is structured with HTML (content), CSS (design), and JavaScript (functionality).  
  - What the frontend (client) and backend (server) are.  
  - How resources (images, scripts) are requested from the server.  
- **Application in pentesting**:  
  - Analyzing source code to find hidden endpoints or sensitive data.  
  - Identifying entry points for attacks such as XSS or injections.
 
## Day 4 - [2025/09/20]
### Section 3 completed: How The Web Works
- **Modules completed:**  
  - HTTP in Detail  
  - How Websites Work  
  - DNS in Detail  
  - Putting it all together  
- **Skills acquired**:  
  - Analysis of HTTP/HTTPS requests and headers.  
  - Source code inspection (HTML, CSS, JS).  
  - DNS resolution and its impact on security.  
- **Next step**: Section 4 - “Linux Fundamentals.”

## Day 4 - [2025/09/20]
### Module: Linux Fundamentals (Part 1)
- **Key commands**:  
  - `ls`, `cd`, `pwd`, `cat`, `echo`, `mkdir`, `rm`.
- **Concepts**:  
  - Linux directory structure (e.g., `/home`, `/etc`).  
  - Absolute vs. relative paths.  
- **Next step**: Linux Fundamentals (Part 2)
