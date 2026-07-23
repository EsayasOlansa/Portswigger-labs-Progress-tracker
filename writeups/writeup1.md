```
██████╗  ██████╗ ██████╗ ████████╗ ███████╗██╗    ██╗██╗ ██████╗  ██████╗ ███████╗██████╗
██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝██║    ██║██║██╔════╝ ██╔════╝ ██╔════╝██╔══██╗
██████╔╝██║   ██║██████╔╝   ██║   ███████╗██║ █╗ ██║██║██║  ███╗██║  ███╗█████╗  ██████╔╝
██╔═══╝ ██║   ██║██╔══██╗   ██║   ╚════██║██║███╗██║██║██║   ██║██║   ██║██╔══╝  ██╔══██╗
██║     ╚██████╔╝██║  ██║   ██║   ███████║╚███╔███╔╝██║╚██████╔╝╚██████╔╝███████╗██║  ██║
╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚══╝╚══╝ ╚═╝ ╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝
```

### 🕵️ Web Security Academy — Lab Tracker

*Pwning labs. Taking notes. Breaking things responsibly.*

---

![Solved](https://img.shields.io/badge/Labs%20Solved-61-informational?style=for-the-badge&logo=target&logoColor=white&color=0A84FF)
![Updated](https://img.shields.io/badge/Last%20Updated-2026--07--19-informational?style=for-the-badge&logo=clockify&logoColor=white&color=F59E0B)
![Level](https://img.shields.io/badge/Level-NEWBIE-informational?style=for-the-badge&logo=hackthebox&logoColor=white&color=22C55E)
![Progress](https://img.shields.io/badge/Overall%20Progress-9.1%25-informational?style=for-the-badge&logo=progress&logoColor=white&color=8B5CF6)
![Tool](https://img.shields.io/badge/Tool-Burp%20Suite-informational?style=for-the-badge&logo=burpsuite&logoColor=white&color=FF6633)

---

## 📖 About

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference.

> Full writeups are reserved for first-time techniques, complex exploits, or custom tooling. See `writeups/` for details.

---

## 📊 Progress Dashboard

| Tier               | Solved | Total | Progress                                                                                  |
| ------------------- | ------ | ----- | ------------------------------------------------------------------------------------------ |
| 🟢 **Apprentice**   | `25`   | `61`  | ![37%](https://img.shields.io/badge/-37.7%25-22C55E?style=flat-square)                     |
| 🟡 **Practitioner** | `34`   | `174` | ![17%](https://img.shields.io/badge/-17.8%25-F59E0B?style=flat-square)                     |
| 🔴 **Expert**       | `2`    | `39`  | ![5%](https://img.shields.io/badge/-5%25-EF4444?style=flat-square)                         |
| ⚡ **Total**         | `61`   | `274` | ![20.4%](https://img.shields.io/badge/-20.4%25-0A84FF?style=flat-square)                   |

## 🗂️ Categories Covered

| Category                          | Solved | Total | Status                                                                      |
| ---------------------------------- | ------ | ----- | ----------------------------------------------------------------------------- |
| 🔐 Authentication vulnerabilities  | `14`   | `14`  | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square)     |
| 💉 SQL injection                   | `11`   | `18`  | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| 🚪 Access control                  | `13`   | `13`  | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square)     |
| 📜 Cross-site scripting            | `7`    | `30`  | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| 📂 Path traversal                  | `6`    | `6`   | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square)     |
| 💻 OS command injection            | `5`    | `5`   | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square)     |
| 🔌 WebSockets                      | `0`    | `3`   | ![Not started](https://img.shields.io/badge/NOT%20STARTED-6B7280?style=flat-square) |
| 📤 File upload vulnerabilities     | `5`    | `7`   | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |

---

## 🗺️ How to Read

| Column       | Description                                    |
| ------------ | ----------------------------------------------- |
| `No`         | Sequential lab number                            |
| `Date`       | When solved `YYYY-MM-DD`                         |
| `Topic`      | Vulnerability category                           |
| `Lab Title`  | Exact name from PortSwigger                      |
| `Difficulty` | `APPRENTICE` · `PRACTITIONER` · `EXPERT`         |
| `Writeup`    | Link to full writeup or `—` for quick solves     |

---

## 🧪 Solved Labs

> 📌 **61 labs solved** · Sorted chronologically · Pending slots reserved below

| No   | Date       | Topic                          | Lab Title                                                                            | Difficulty   | Writeup |
| ---- | ---------- | ------------------------------- | -------------------------------------------------------------------------------------- | ------------- | ------- |
| `01` | 2026-06-17 | 💉 SQL Injection                | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data          | APPRENTICE    | —       |
| `02` | 2026-06-17 | 💉 SQL Injection                | SQL injection vulnerability allowing login bypass                                      | APPRENTICE    | —       |
| `03` | 2026-06-17 | 💉 SQL Injection                | SQL injection attack, querying the database type and version on Oracle                 | PRACTITIONER  | —       |
| `04` | 2026-06-17 | 💉 SQL Injection                | SQL injection attack, querying the database type and version on MySQL and Microsoft    | PRACTITIONER  | —       |
| `05` | 2026-06-17 | 💉 SQL Injection                | SQL injection attack, listing the database contents on non-Oracle databases            | PRACTITIONER  | —       |
| `06` | 2026-06-17 | 💉 SQL Injection                | SQL injection attack, listing the database contents on Oracle                          | PRACTITIONER  | —       |
| `07` | 2026-06-17 | 💉 SQL Injection                | SQL injection UNION attack, determining the number of columns returned by the query    | PRACTITIONER  | —       |
| `08` | 2026-06-17 | 💉 SQL Injection                | SQL injection UNION attack, finding a column containing text                           | PRACTITIONER  | —       |
| `09` | 2026-06-17 | 💉 SQL Injection                | SQL injection UNION attack, retrieving data from other tables                          | PRACTITIONER  | —       |
| `10` | 2026-06-17 | 💉 SQL Injection                | SQL injection UNION attack, retrieving multiple values in a single column              | PRACTITIONER  | —       |
| `11` | 2026-06-17 | 💉 SQL Injection                | Blind SQL injection with conditional responses                                         | PRACTITIONER  | —       |
| `12` | 2026-06-22 | 🔐 Authentication               | Username enumeration via different responses                                           | APPRENTICE    | —       |
| `13` | 2026-06-22 | 🔐 Authentication               | 2FA simple bypass                                                                       | APPRENTICE    | —       |
| `14` | 2026-06-23 | 🔐 Authentication               | Password reset broken logic                                                            | APPRENTICE    | —       |
| `15` | 2026-06-23 | 🔐 Authentication               | Username enumeration via subtly different responses                                    | PRACTITIONER  | —       |
| `16` | 2026-06-23 | 🔐 Authentication               | Username enumeration via response timing                                               | PRACTITIONER  | —       |
| `17` | 2026-06-24 | 🔐 Authentication               | Broken brute-force protection, IP block                                                | PRACTITIONER  | —       |
| `18` | 2026-06-24 | 🔐 Authentication               | Username enumeration via account lock                                                  | PRACTITIONER  | —       |
| `19` | 2026-06-25 | 🔐 Authentication               | 2FA broken logic                                                                        | PRACTITIONER  | —       |
| `20` | 2026-06-25 | 🔐 Authentication               | Brute-forcing a stay-logged-in cookie                                                  | PRACTITIONER  | —       |
| `21` | 2026-06-25 | 🔐 Authentication               | Offline password cracking                                                              | PRACTITIONER  | —       |
| `22` | 2026-06-26 | 🔐 Authentication               | Broken brute-force protection, multiple credentials per request                        | EXPERT        | —       |
| `23` | 2026-06-27 | 🔐 Authentication               | Password reset poisoning via middleware                                                | PRACTITIONER  | —       |
| `24` | 2026-06-27 | 🔐 Authentication               | Password brute-force via password change                                               | PRACTITIONER  | —       |
| `25` | 2026-06-28 | 🔐 Authentication               | 2FA bypass using a brute-force attack                                                  | EXPERT        | —       |
| `26` | 2026-06-29 | 📜 Cross-site scripting          | Reflected XSS into HTML context with nothing encoded                                   | APPRENTICE    | —       |
| `27` | 2026-06-29 | 📜 Cross-site scripting          | Stored XSS into HTML context with nothing encoded                                      | APPRENTICE    | —       |
| `28` | 2026-06-29 | 📂 Path traversal                | File path traversal, simple case                                                       | APPRENTICE    | —       |
| `29` | 2026-06-30 | 📜 Cross-site scripting          | DOM XSS in document.write sink using source location.search                            | APPRENTICE    | —       |
| `30` | 2026-06-30 | 📜 Cross-site scripting          | DOM XSS in innerHTML sink using source location.search                                 | APPRENTICE    | —       |
| `31` | 2026-06-30 | 📂 Path traversal                | File path traversal, traversal sequences blocked with absolute path bypass             | PRACTITIONER  | —       |
| `32` | 2026-06-30 | 📂 Path traversal                | File path traversal, traversal sequences stripped non-recursively                      | PRACTITIONER  | —       |
| `33` | 2026-07-01 | 📜 Cross-site scripting          | DOM XSS in jQuery anchor href attribute sink using location.search source              | APPRENTICE    | —       |
| `34` | 2026-07-01 | 📜 Cross-site scripting          | DOM XSS in jQuery selector sink using a hashchange event                               | APPRENTICE    | —       |
| `35` | 2026-07-02 | 📜 Cross-site scripting          | Reflected XSS into attribute with angle brackets HTML-encoded                          | APPRENTICE    | —       |
| `36` | 2026-07-02 | 📂 Path traversal                | File path traversal, traversal sequences stripped with superfluous URL-decode          | PRACTITIONER  | —       |
| `37` | 2026-07-02 | 📂 Path traversal                | File path traversal, validation of start of path                                       | PRACTITIONER  | —       |
| `38` | 2026-07-03 | 📂 Path traversal                | File path traversal, validation of file extension with null byte bypass                | PRACTITIONER  | —       |
| `39` | 2026-07-03 | 💻 OS command injection          | OS command injection, simple case                                                      | APPRENTICE    | —       |
| `40` | 2026-07-04 | 💻 OS command injection          | Blind OS command injection with time delays                                            | PRACTITIONER  | —       |
| `41` | 2026-07-04 | 💻 OS command injection          | Blind OS command injection with output redirection                                     | PRACTITIONER  | —       |
| `42` | 2026-07-05 | 💻 OS command injection          | Blind OS command injection with out-of-band interaction                                | PRACTITIONER  | —       |
| `43` | 2026-07-05 | 💻 OS command injection          | Blind OS command injection with out-of-band data exfiltration                          | PRACTITIONER  | —       |
| `44` | 2026-07-06 | 🚪 Access control                | Unprotected admin functionality                                                        | APPRENTICE    | —       |
| `45` | 2026-06-07 | 🚪 Access control                | Unprotected admin functionality with unpredictable URL                                 | APPRENTICE    | —       |
| `46` | 2026-06-07 | 🚪 Access control                | User role controlled by request parameter                                              | APPRENTICE    | —       |
| `47` | 2026-06-08 | 🚪 Access control                | User role can be modified in user profile                                              | APPRENTICE    | —       |
| `48` | 2026-06-08 | 🚪 Access control                | User ID controlled by request parameter                                                | APPRENTICE    | —       |
| `49` | 2026-06-08 | 🚪 Access control                | User ID controlled by request parameter, with unpredictable user IDs                   | APPRENTICE    | —       |
| `50` | 2026-06-09 | 🚪 Access control                | User ID controlled by request parameter with data leakage in redirect                  | APPRENTICE    | —       |
| `51` | 2026-06-09 | 🚪 Access control                | User ID controlled by request parameter with password disclosure                       | APPRENTICE    | —       |
| `52` | 2026-06-09 | 🚪 Access control                | Insecure direct object references                                                      | APPRENTICE    | —       |
| `53` | 2026-06-10 | 🚪 Access control                | URL-based access control can be circumvented                                           | PRACTITIONER  | —       |
| `54` | 2026-06-11 | 🚪 Access control                | Method-based access control can be circumvented                                        | PRACTITIONER  | —       |
| `55` | 2026-06-11 | 🚪 Access control                | Multi-step process with no access control on one step                                  | PRACTITIONER  | —       |
| `56` | 2026-07-12 | 🚪 Access control                | Referer-based access control                                                           | PRACTITIONER  | —       |
| `57` | 2026-07-13 | 📤 File upload vulnerabilities   | Remote code execution via web shell upload                                             | APPRENTICE    | —       |
| `58` | 2026-07-14 | 📤 File upload vulnerabilities   | Web shell upload via Content-Type restriction bypass                                   | APPRENTICE    | —       |
| `59` | 2026-07-15 | 📤 File upload vulnerabilities   | Web shell upload via path traversal                                                    | PRACTITIONER  | —       |
| `60` | 2026-07-15 | 📤 File upload vulnerabilities   | Web shell upload via obfuscated file extension                                         | PRACTITIONER  | —       |
| `61` | 2026-07-16 | 📤 File upload vulnerabilities   | Remote code execution via polyglot web shell upload                                    | PRACTITIONER  | —       |
| `62` | —          | —                                | *Pending...*                                                                            | —             | —       |
| `63` | —          | —                                | *Pending...*                                                                            | —             | —       |
| `64` | —          | —                                | *Pending...*                                                                            | —             | —       |
| `65` | —          | —                                | *Pending...*                                                                            | —             | —       |

---

*Keep hacking. Stay curious. Never stop learning.* 🔓

[![PortSwigger](https://img.shields.io/badge/PortSwigger-Web%20Security%20Academy-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)](https://portswigger.net/web-security)