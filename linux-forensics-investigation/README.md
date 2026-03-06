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

System Integrity
- rkhunter
- chkrootkit

File Analysis
- ascii
- xxd
- strings

Disk Image Forensics
- The Sleuth Kit

## Investigation Workflow

1. Perform passive operating system fingerprinting using p0f.
2. Identify network devices using arp-scan and nmap.
3. Analyze swap memory artifacts using swap_digger.
4. Attempt credential extraction using mimipenguin.
5. Check system integrity using rkhunter and chkrootkit.
6. Inspect file contents using ascii, xxd, and strings.
7. Analyze disk image artifacts using Sleuth Kit tools.

## Findings

The investigation demonstrated how Linux forensic tools can be used to identify network activity, detect rootkits, and analyze file system metadata within forensic disk images.

## Skills Demonstrated

- Linux forensic investigation
- Network enumeration
- Rootkit detection
- Artifact recovery
- Disk image analysis
