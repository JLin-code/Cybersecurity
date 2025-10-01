# Cybersecurity

This repository covers essential cybersecurity concepts and attack vectors taught in class at SUNY New Paltz (CPS493-02)

## System Security

### Linux Security Basics
Fundamental security concepts in Linux operating systems including:
- User and group permissions
- File system security (rwx permissions)
- Access control mechanisms
- Security policies and enforcement
- Process isolation and privilege separation

### Set-UID Programs
Understanding privileged programs and their security implications:
- How Set-UID bits work
- Privilege escalation mechanisms
- Common vulnerabilities in Set-UID programs
- Security best practices for privileged execution
- Attack vectors targeting Set-UID binaries

### Environment Variables and Attack
Exploitation techniques using environment variables:
- How environment variables affect program execution
- PATH manipulation attacks
- LD_PRELOAD and library injection
- Shell injection through environment variables
- Mitigation strategies and secure coding practices

### Buffer Overflow Attack
Memory corruption vulnerabilities and exploitation:
- Stack-based buffer overflows
- Heap-based buffer overflows
- Return address manipulation
- Shellcode injection techniques
- Modern protections (ASLR, DEP, stack canaries)

---

## Web Security

### Web Security Basics
Core concepts of web application security:
- HTTP/HTTPS protocol security
- Session management
- Authentication and authorization
- Input validation and sanitization
- Secure coding principles for web applications

### Cross Site Request Forgery (CSRF)
Understanding and preventing CSRF attacks:
- How CSRF attacks work
- State-changing operations vulnerability
- CSRF token implementation
- SameSite cookie attributes
- Defense mechanisms and best practices

### Cross-Site Scripting (XSS) Attack
Client-side injection attacks:
- Reflected XSS attacks
- Stored XSS attacks
- DOM-based XSS
- XSS payload construction
- Content Security Policy (CSP) as mitigation

### SQL Injection Attack
Database security and injection prevention:
- Classic SQL injection techniques
- Blind SQL injection
- Union-based attacks
- Time-based attacks
- Prepared statements and parameterized queries

---

## Network Security

### Network Security Basics
Foundational network security concepts:
- Network protocols and their vulnerabilities
- Encryption and secure communication
- Network authentication mechanisms
- Intrusion detection and prevention
- Network monitoring and logging

### Attacks in Networking
Common network-based attack vectors:
- Man-in-the-middle attacks
- ARP spoofing and poisoning
- DNS attacks and cache poisoning
- Network sniffing and packet analysis
- Denial of Service (DoS) attacks

### Reconnaissance
Information gathering and attack preparation:
- Passive reconnaissance techniques
- Active scanning and enumeration
- Footprinting and fingerprinting
- Social engineering aspects
- OSINT (Open Source Intelligence) gathering

### Firewalls
Network perimeter defense mechanisms:
- Firewall types and architectures
- Rule configuration and management
- Stateful vs stateless filtering
- Application layer filtering
- Firewall evasion techniques and countermeasures
