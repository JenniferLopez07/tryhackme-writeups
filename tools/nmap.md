# Module: Nmap

## 🎯 Objective
Learn how to use Nmap for network discovery, service enumeration, and vulnerability detection.

---

## Nmap Basics
- Practiced scanning hosts with `nmap <target>`.
- Learned common flags:
  - `-sS` (SYN scan)
  - `-sU` (UDP scan)
  - `-p` (port specification)
- Understood the difference between open, closed, and filtered ports.

---

## Nmap Advanced Scans
- Used `-sV` for service/version detection.
- Practiced OS fingerprinting with `-O`.
- Learned about timing templates (`-T0` to `-T5`) and their trade‑offs.

---

## Nmap Scripting Engine (NSE)
- Explored Nmap’s scripting capabilities.
- Ran vulnerability detection scripts (`--script vuln`).
- Used NSE for authentication checks and brute force attempts.

---

## 📚 Lessons Learned
- Nmap is the most versatile tool for enumeration in penetration testing.
- Basic scans reveal open ports, while advanced scans provide deeper context.
- NSE extends Nmap into a lightweight vulnerability scanner.
- Mastery of Nmap is essential for both red teamers and defenders.

---

## 🛠️ Commands Practiced
- `nmap -sS <target>`
- `nmap -sU <target>`
- `nmap -sV -O <target>`
- `nmap --script vuln <target>`


