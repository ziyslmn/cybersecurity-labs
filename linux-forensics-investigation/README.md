# Linux System Forensics Investigation

## Objective
The goal of this investigation was to analyze Linux system artifacts, network activity, and file system evidence using forensic tools commonly used in digital investigations.

## Tools Used

Network Analysis
- p0f
- arp-scan
- nmap

Artifact Recovery
- swap_digger
- mimipenguin

System Integrity & Rootkit Detection
- rkhunter
- chkrootkit

File Analysis
- ascii
- xxd
- strings

Disk Image Forensics
- The Sleuth Kit
- fls
- fsstat
- ils
- img_stat
- fiwalk

## Investigation Activities

The investigation included several Linux forensic techniques:

- Passive operating system fingerprinting using **p0f**
- Network discovery and device enumeration using **arp-scan** and **nmap**
- Analysis of swap memory artifacts using **swap_digger**
- Extraction of credentials from active sessions using **mimipenguin**
- Rootkit detection using **rkhunter** and **chkrootkit**
- File content inspection using **ascii**, **xxd**, and **strings**
- Disk image forensic analysis using **The Sleuth Kit**

## Findings

The analysis demonstrated how Linux forensic tools can be used to identify network activity, recover sensitive artifacts from system memory, detect potential rootkits, and examine file system metadata within forensic disk images.

## Skills Demonstrated

- Linux system forensic analysis
- Network discovery and enumeration
- Artifact recovery and credential extraction
- Rootkit detection
- Disk image forensic investigation
