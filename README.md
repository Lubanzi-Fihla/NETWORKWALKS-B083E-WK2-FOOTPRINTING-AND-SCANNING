# NETWORKWALKS-B083E-WK2-FOOTPRINTING-AND-SCANNING
# Week 2 Cybersecurity Project

## Intern Details

**Name:** Lubanzi Fihla

**Batch:** B083

## Modules Completed

- W2-PM4: Footprinting with theHarvester
- W2-PM5: Network Scanning with Zenmap

---

## Objective

To gain practical experience in information gathering and network reconnaissance using cybersecurity tools.

---

## Tools Used

- Kali Linux
- theHarvester
- Zenmap
- Nmap

---

## theHarvester Commands

```bash
theHarvester -d microsoft.com -l 1000 -b baidu

theHarvester -d microsoft.com -l 50 -b all
```

---

## Zenmap Scan

Target:

```text
10.0.0.0/24
```

Profile:

```text
Ping Scan
```

---

## Findings

### theHarvester

- Identified publicly available Microsoft subdomains.
- Collected host information.
- Performed passive reconnaissance.

### Zenmap

- Found 2 live hosts.
- Identified network devices.
- Collected IP address information.

### Live Hosts

```text
10.0.0.1
10.0.0.2
```

### MAC Address

```text
52:54:00:12:35:00
```

---

## Lessons Learned

- Footprinting
- OSINT
- Reconnaissance
- Host Discovery
- Network Enumeration
- Zenmap Usage

``
