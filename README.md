<div align="center">

```
██████╗  ██████╗ ██████╗ ████████╗███████╗██╗    ██╗██╗ ██████╗  ██████╗ ███████╗██████╗
██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝██║    ██║██║██╔════╝ ██╔════╝ ██╔════╝██╔══██╗
██████╔╝██║   ██║██████╔╝   ██║   ███████╗██║ █╗ ██║██║██║  ███╗██║  ███╗█████╗  ██████╔╝
██╔═══╝ ██║   ██║██╔══██╗   ██║   ╚════██║██║███╗██║██║██║   ██║██║   ██║██╔══╝  ██╔══██╗
██║     ╚██████╔╝██║  ██║   ██║   ███████║╚███╔███╔╝██║╚██████╔╝╚██████╔╝███████╗██║  ██║
╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚══╝╚══╝ ╚═╝ ╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝
```

### 🕵️ Web Security Academy — Lab Tracker

*Pwning labs. Taking notes. Breaking things responsibly.*

---

![Solved](https://img.shields.io/badge/Labs%20Solved-25-informational?style=for-the-badge&logo=target&logoColor=white&color=0A84FF)
![Updated](https://img.shields.io/badge/Last%20Updated-2026--06--28-informational?style=for-the-badge&logo=clockify&logoColor=white&color=F59E0B)
![Level](https://img.shields.io/badge/Level-NEWBIE-informational?style=for-the-badge&logo=hackthebox&logoColor=white&color=22C55E)
![Progress](https://img.shields.io/badge/Overall%20Progress-9.1%25-informational?style=for-the-badge&logo=progress&logoColor=white&color=8B5CF6)
![Tool](https://img.shields.io/badge/Tool-Burp%20Suite-informational?style=for-the-badge&logo=burpsuite&logoColor=white&color=FF6633)

</div>

---

## 📖 About

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference.

> Full writeups are reserved for first-time techniques, complex exploits, or custom tooling. See `platforms/portswigger/` for details.

---

## 📊 Progress Dashboard

<div align="center">

| Tier | Solved | Total | Progress |
|:----:|:------:|:-----:|:--------:|
| 🟢 **Apprentice** | `5` | `61` | ![8%](https://img.shields.io/badge/-8%25-22C55E?style=flat-square) |
| 🟡 **Practitioner** | `18` | `174` | ![10%](https://img.shields.io/badge/-10%25-F59E0B?style=flat-square) |
| 🔴 **Expert** | `2` | `39` | ![5%](https://img.shields.io/badge/-5%25-EF4444?style=flat-square) |
| ⚡ **Total** | `25` | `274` | ![9%](https://img.shields.io/badge/-9%25-0A84FF?style=flat-square) |

</div>

---

## 🗂️ Categories Covered

| Category | Solved | Total | Status |
|----------|:------:|:-----:|--------|
| 🔐 Authentication vulnerabilities | `14` | `14` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| 💉 SQL injection | `11` | `18` | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| 🚪 Access control | `0` | `13` | ![Not started](https://img.shields.io/badge/NOT%20STARTED-6B7280?style=flat-square) |

---

## 🗺️ How to Read

| Column | Description |
|--------|-------------|
| `No` | Sequential lab number |
| `Date` | When solved `YYYY-MM-DD` |
| `Topic` | Vulnerability category |
| `Lab Title` | Exact name from PortSwigger |
| `Difficulty` | `APPRENTICE` · `PRACTITIONER` · `EXPERT` |
| `Writeup` | Link to full writeup or `N/A` for quick solves |

---

## 🧪 Solved Labs

> 📌 **25 labs solved** · Sorted chronologically · Pending slots reserved below

| No | Date | Topic | Lab Title | Difficulty | Writeup |
|----|------|-------|-----------|:----------:|:-------:|
| `01` | 2026-06-17 | 💉 SQL Injection | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `02` | 2026-06-17 | 💉 SQL Injection | SQL injection vulnerability allowing login bypass | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `03` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, querying the database type and version on Oracle | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `04` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, querying the database type and version on MySQL and Microsoft | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `05` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, listing the database contents on non-Oracle databases | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `06` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, listing the database contents on Oracle | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `07` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, determining the number of columns returned by the query | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `08` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, finding a column containing text | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `09` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, retrieving data from other tables | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `10` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, retrieving multiple values in a single column | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `11` | 2026-06-17 | 💉 SQL Injection | Blind SQL injection with conditional responses | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `12` | 2026-06-22 | 🔐 Authentication | Username enumeration via different responses | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `13` | 2026-06-22 | 🔐 Authentication | 2FA simple bypass | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `14` | 2026-06-23 | 🔐 Authentication | Password reset broken logic | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `15` | 2026-06-23 | 🔐 Authentication | Username enumeration via subtly different responses | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `16` | 2026-06-23 | 🔐 Authentication | Username enumeration via response timing | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `17` | 2026-06-24 | 🔐 Authentication | Broken brute-force protection, IP block | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `18` | 2026-06-24 | 🔐 Authentication | Username enumeration via account lock | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `19` | 2026-06-25 | 🔐 Authentication | 2FA broken logic | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `20` | 2026-06-25 | 🔐 Authentication | Brute-forcing a stay-logged-in cookie | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `21` | 2026-06-25 | 🔐 Authentication | Offline password cracking | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `22` | 2026-06-26 | 🔐 Authentication | Broken brute-force protection, multiple credentials per request | ![](https://img.shields.io/badge/EXPERT-EF4444?style=flat-square) | — |
| `23` | 2026-06-27 | 🔐 Authentication | Password reset poisoning via middleware | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `24` | 2026-06-27 | 🔐 Authentication | Password brute-force via password change | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `25` | 2026-06-28 | 🔐 Authentication | 2FA bypass using a brute-force attack | ![](https://img.shields.io/badge/EXPERT-EF4444?style=flat-square) | — |
| `26` | 2026-06-29 |  Cross-site scripting | Reflected XSS into HTML context with nothing encoded | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `27` | 2026-06-29 | Cross-site scripting | Stored XSS into HTML context with nothing encoded | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `28` | 2026-06-29 | — | *Pending...* | — | — |
| `27` | 2026-06-29 | — | *Pending...* | — | — |
| `28` | 2026-06-29 | — | *Pending...* | — | — |
| `27` | 2026-06-30 | — | DOM XSS in document.write sink using source location.search | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `28` | 2026-06-30 | — | DOM XSS in innerHTML sink using source location.search | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `27` | 2026-06-29 | — | *Pending...* | — | — |
| `27` | 2026-06-29 | — | *Pending...* | — | — |
| `28` | 2026-06-01 | — | DOM XSS in jQuery anchor href attribute sink using location.search source | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `27` | 2026-06-02 | — | DOM XSS in jQuery selector sink using a hashchange event | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `28` | 2026-06-02 | — | Reflected XSS into attribute with angle brackets HTML-encoded | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `29` | — | — | *Pending...* | — | — |
| `30` | — | — | *Pending...* | — | — |
| `31` | — | — | *Pending...* | — | — |
| `32` | — | — | *Pending...* | — | — |
| `33` | — | — | *Pending...* | — | — |
| `34` | — | — | *Pending...* | — | — |
| `35` | — | — | *Pending...* | — | — |
| `36` | — | — | *Pending...* | — | — |
| `37` | — | — | *Pending...* | — | — |
| `38` | — | — | *Pending...* | — | — |
| `39` | — | — | *Pending...* | — | — |
| `40` | — | — | *Pending...* | — | — |

---

<div align="center">

*Keep hacking. Stay curious. Never stop learning.* 🔓

[![PortSwigger](https://img.shields.io/badge/PortSwigger-Web%20Security%20Academy-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)](https://portswigger.net/web-security)

</div>
