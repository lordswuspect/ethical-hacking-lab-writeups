
# Ethical Hacking Lab Write-Ups

A collection of hands-on offensive security labs performed in isolated virtual lab environments (Kali Linux + deliberately vulnerable target machines such as Metasploitable2). Each write-up covers the vulnerability, the exploitation process, findings, and remediation recommendations.

**Disclaimer:** All labs were performed strictly in isolated, self-hosted virtual environments for educational purposes only. No real-world systems were accessed or affected.

## Labs

| Lab | Vulnerability | Summary |
|---|---|---|
| [NFS Share Exploitation](./nfs-share-exploitation) | Misconfigured NFS export (open to all hosts) | Mounted an unauthenticated, world-exported filesystem and extracted database credentials leading to full data exposure |
| [vsFTPd Backdoor Exploitation](./vsftpd-backdoor-exploit) | Backdoored vsFTPd 2.3.4 service | Exploited a known backdoor in the FTP service to gain unauthorized shell access |

## Tools Used
- Kali Linux
- Metasploitable2
- NFS, MySQL, FTP protocol tooling

## Skills Demonstrated
- Network service enumeration
- Exploiting misconfigurations and known vulnerabilities
- Post-exploitation data extraction
- Vulnerability documentation & reporting
