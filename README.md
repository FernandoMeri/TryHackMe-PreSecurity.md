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

## Day 4 - [2025/09/20]
### Module: Linux Fundamentals (Part 2)
- **Key commands**:
- `grep`: Search for text patterns.
- `chmod`: Manage permissions (e.g., `chmod 755 file`).
- `sudo`: Run as root.
- `|` (pipe): Chain commands.  
- **Concepts**:  
  - Numeric permissions (755 = rwxr-xr-x).  
  - Filtering outputs with `grep` and `|`.  
- **Next step**: Linux Fundamentals (Part 3)

## Day 4 - [2025/09/20]
### Module: Linux Fundamentals (Part 3) - ✅ COMPLETED
- **Key learning points**:
- Process management (`ps`, `kill`, `top`).  
  - Scheduling tasks with `cron` (`crontab -e`).  
  - Basic scripting in Bash.  
  - Package management with `apt` and repositories.  
- **Next step**: Windows Fundamentals (Section 5).

## Day 4 - [2025/09/20]
### Modules completed:
- **Network Fundamentals**: DNS, HTTP, networks.
- **How The Web Works**: HTML, HTTP, servers.
- **Linux Fundamentals (Parts 1, 2, 3)**: 
  - Commands: `ps`, `kill`, `cron`, `apt`.
  - Basic scripting and process management.
- **Next goal**: Windows Fundamentals.

## Day 5 - [2025/09/21]
# TryHackMe - Windows Fundamentals (Parts 1, 2, and 3)

## 📌 Summary
This repository documents my learning in the **Windows Fundamentals** modules from TryHackMe, covering everything from the graphical interface to advanced administration and security tools.

## 🧠 Key Concepts Learned

### Part 1: System Basics
- **Desktop and GUI**: Components such as the Start Menu, Taskbar, Notification Area, and customization:cite[6].
- **File System**: Using File Explorer, directory structure, basic permissions.
- **UAC (User Account Control)**: Permission levels and security alerts.
- **Control Panel and Settings**: System, network, and hardware settings.
- **Task Manager**: Process, performance, and service management.

### Part 2: Advanced Utilities
- **System Tools**:
  - `msconfig` (System Configuration): Startup, services, and boot management.
  - `compmgmt.msc` (Computer Management): Users, disks, services:cite[7].
  - **Resource Monitor**: Real-time monitoring of CPU, RAM, disk, and network.
- **Other Utilities**: Management console, diagnostic tools.

### Part 3: Security and Maintenance
- **Windows Updates**: Importance of security patches.
- **Windows Defender**: Protection against viruses and threats:cite[6].
- **Windows Firewall**: Configuring network rules.
- **BitLocker**: Disk encryption and key management.
- **Volume Shadow Copy**: Backups and restoration.
- **Device Security**: Password and encryption policies.

## ⚡ Useful Commands and Tools
### PowerShell (Introduction)
- `Get-Process`: List active processes.
- `Get-Service`: View system services.
- `Start-Service` / `Stop-Service`: Start/stop services:cite[10].
- `Get-EventLog`: View event logs.

### Network Commands
- `ipconfig`: View IP configuration.
- `ping`: Check connectivity.
- `netstat`: Network connection status.

### Graphical Tools
- **Windows Defender**: Real-time scanning and protection.
- **Device Manager**: Hardware management.
- **Registry Editor**: Advanced system settings (use with caution!).

## 🔍 Application in Cybersecurity
- **Windows Hardening**: Disable unnecessary services, configure firewall.
- **Process Monitoring**: Identify malicious processes with `Get-Process`.
- **Event Analysis**: Search for suspicious events in logs (`Get-EventLog`).
- **Data Encryption**: Use BitLocker to protect sensitive information.

## 📂 Practical Exercises Performed
1. **Firewall Configuration**: Create rules to allow/block traffic.
2. **Service Management**: Disable non-critical services to reduce the attack surface.
3. **BitLocker**: Simulate USB encryption.
4. **Volume Shadow Copy**: Restoring files from a backup.

## 🚀 Next Steps
- Delve deeper into **PowerShell** for task automation:cite[10].
- Explore **Active Directory** in corporate environments.
- Practice with Windows pentesting labs (e.g., exploiting vulnerable services).

## 📚 Resources
- [TryHackMe - Windows Fundamentals](https://tryhackme.com/module/windows-fundamentals)
- [Microsoft Docs - Windows Security](https://learn.microsoft.com/en-us/windows/security/)
- [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)

---

**Notes**:
- This content is based on TryHackMe modules and official Microsoft documentation.
- Updated as of September 21, 2025.
