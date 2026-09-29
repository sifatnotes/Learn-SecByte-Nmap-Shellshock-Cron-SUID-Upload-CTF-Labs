# Learn-SecByte-Nmap-Shellshock-Cron-SUID-Upload-CTF-Labs
Hands-on cybersecurity and CTF labs covering Nmap service discovery, Linux privilege escalation, cron security, SUID shells, Shellshock, PTY techniques, shell access, and file upload vulnerabilities.
# Learn SecByte Nmap, Shellshock, Cron, SUID & Upload CTF Labs

A focused collection of hands-on cybersecurity and CTF labs from Learn SecByte covering network service enumeration, Linux privilege escalation, cron security, SUID shells, Shellshock, PTY techniques, shell access, and file upload vulnerabilities.

These labs are useful for cybersecurity students, CTF players, penetration testers, SOC analysts, and security learners building practical skills in controlled environments.

## Introduction

Practical cybersecurity training requires more than understanding security concepts. CTF and vulnerability labs provide controlled environments for practicing reconnaissance, enumeration, exploitation analysis, shell handling, and Linux privilege escalation.

This repository organizes Learn SecByte labs around Nmap discovery, Linux shells, cron and SUID escalation, Shellshock, PTY techniques, and upload-related security testing.

## Lab Collection

| Lab | Topic / Category | Tool or Technique |
|---|---|---|
| [Nmap Service Hunt](https://learn.secbyte.org/ctf/nmap-service-hunt) | Service Enumeration / Reconnaissance | Nmap |
| [Fall Into Discovery](https://learn.secbyte.org/ctf/fall-into-discovery) | Discovery / Reconnaissance | Enumeration |
| [HMS-1 Root Path](https://learn.secbyte.org/ctf/hms-1-root-path) | Linux Privilege Escalation | Root Access |
| [Tar Trap to Root Shell](https://learn.secbyte.org/ctf/tar-trap-to-root-shell) | Linux Privilege Escalation | tar |
| [Cron Lockdown](https://learn.secbyte.org/ctf/cron-lockdown) | Cron Security | Cron |
| [SUID Shells and Cron Escapes](https://learn.secbyte.org/ctf/suid-shells-and-cron-escapes) | Privilege Escalation | SUID / Cron |
| [HMS Shellshock](https://learn.secbyte.org/ctf/hms-shellshock) | Web / Command Injection | Shellshock |
| [PTY Pivot](https://learn.secbyte.org/ctf/pty-pivot) | Shell Stabilization | PTY |
| [Shellshock to Root 2](https://learn.secbyte.org/ctf/shellshock-to-root-2) | Privilege Escalation / Exploitation | Shellshock |
| [Shellstream](https://learn.secbyte.org/ctf/shellstream) | Shell Access | Shell |
| [Shell Shock Upload](https://learn.secbyte.org/ctf/shell-shock-upload) | Web Exploitation / File Upload | Shellshock / Upload |
| [Upload Trap](https://learn.secbyte.org/ctf/upload-trap) | Web Security / File Upload | Upload Testing |

> Difficulty and CVE identifiers are not specified by the supplied lab URLs, so they are not assigned here.

## Direct Lab Links

1. https://learn.secbyte.org/ctf/nmap-service-hunt
2. https://learn.secbyte.org/ctf/fall-into-discovery
3. https://learn.secbyte.org/ctf/hms-1-root-path
4. https://learn.secbyte.org/ctf/tar-trap-to-root-shell
5. https://learn.secbyte.org/ctf/cron-lockdown
6. https://learn.secbyte.org/ctf/suid-shells-and-cron-escapes
7. https://learn.secbyte.org/ctf/hms-shellshock
8. https://learn.secbyte.org/ctf/pty-pivot
9. https://learn.secbyte.org/ctf/shellshock-to-root-2
10. https://learn.secbyte.org/ctf/shellstream
11. https://learn.secbyte.org/ctf/shell-shock-upload
12. https://learn.secbyte.org/ctf/upload-trap

## Categories

### Network Reconnaissance
- Nmap service enumeration
- Network and service discovery
- Initial attack-surface identification

### Linux Privilege Escalation
- Root-path investigation
- SUID-based escalation
- Cron-related privilege escalation
- `tar`-related privilege escalation

### Shellshock
- Shellshock exploitation concepts
- Shell access
- Shellshock-to-root attack paths
- Shellshock-related upload testing

### Shell Management
- PTY techniques
- Shell stabilization
- Interactive shell handling

### File Upload Security
- Upload attack surfaces
- Upload validation testing
- Shell-oriented upload vulnerabilities

## Learning Path

A practical sequence for this collection is:

1. Start with **Nmap Service Hunt** to practice service enumeration.
2. Continue with **Fall Into Discovery** for broader discovery skills.
3. Study **HMS-1 Root Path** and **Tar Trap to Root Shell** for Linux privilege escalation.
4. Practice **Cron Lockdown** and **SUID Shells and Cron Escapes** to understand common Linux escalation paths.
5. Explore **HMS Shellshock** and **Shellshock to Root 2** to study Shellshock-based exploitation.
6. Use **PTY Pivot** and **Shellstream** to develop shell-handling skills.
7. Finish with **Shell Shock Upload** and **Upload Trap** for web upload security practice.

## How to Use the Labs

- Use these labs only in authorized and controlled environments.
- Read the objective and understand the target before testing.
- Begin with reconnaissance and service enumeration.
- Record discovered ports, services, paths, and potential attack surfaces.
- Analyze privilege boundaries before attempting escalation.
- Practice shell stabilization when an unstable shell is obtained.
- Document commands, observations, vulnerabilities, and remediation ideas.
- Avoid applying techniques against systems without explicit authorization.

## Skills Covered

- Network reconnaissance
- Nmap service enumeration
- Linux enumeration
- Linux privilege escalation
- SUID security
- Cron security
- Shellshock vulnerability concepts
- PTY and shell stabilization
- Shell access
- File upload security testing
- CTF methodology
- Ethical penetration testing

## Learn SecByte

These labs are provided through Learn SecByte's cybersecurity learning platform. Use the linked lab pages for the original exercises and their current instructions.

## Disclaimer

This repository is intended for cybersecurity education, CTF practice, and authorized security testing. Do not use these techniques against systems, networks, applications, or accounts without explicit permission. The repository does not provide unauthorized access, stolen credentials, or exploit instructions for real-world targets.
