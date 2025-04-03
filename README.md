# CTF Toolkit

Welcome to the **CTF Toolkit**! This repository is a curated collection of tools, techniques, and resources to help you excel in Capture The Flag (CTF) competitions. It covers key domains like cryptography, web exploitation, binary exploitation, reverse engineering, and forensics. Perfect for both beginners and advanced participants!

---

## Table of Contents
1. [Cryptography](#cryptography)
2. [Web Exploitation](#web-exploitation)
3. [Binary Exploitation](#binary-exploitation)
4. [Reverse Engineering](#reverse-engineering)
5. [Forensics](#forensics)
6. [General Purpose Tools](#general-purpose-tools)
7. [Practice Platforms](#practice-platforms)
8. [CTF Writeups & Resources](#ctf-writeups--resources)
9. [Miscellaneous](#miscellaneous)

---

## Cryptography

### **Tools**
- [CyberChef](https://gchq.github.io/CyberChef/) - Versatile tool for encoding, decoding, and cryptanalysis.
- [hashcat](https://hashcat.net/hashcat/) - Password cracking using GPUs.
- [John the Ripper](https://www.openwall.com/john/) - Password cracking tool.
- [OpenSSL](https://www.openssl.org/) - Analyze or manipulate cryptographic algorithms.
- [RSACTF-Tool](https://github.com/Ganapati/RsaCtfTool) - Exploit RSA vulnerabilities.
- [FeatherDuster](https://github.com/nccgroup/featherduster) - Cryptanalysis automation.
- [Cryptohack](https://cryptohack.org/) - Interactive cryptography challenges.

### **Techniques**
- Frequency analysis for substitution ciphers.
- Modular arithmetic for RSA challenges.
- Breaking Caesar, Vigenère, XOR ciphers, etc.

---

## Web Exploitation

### **Tools**
- [Burp Suite](https://portswigger.net/burp) - Proxy for analyzing and manipulating HTTP requests.
- [Postman](https://www.postman.com/) - API testing and request crafting.
- [sqlmap](https://sqlmap.org/) - Automates SQL injection attacks.
- [Dirb](https://tools.kali.org/web-applications/dirb) / [Dirbuster](https://www.kali.org/tools/dirbuster/) - Directory and file enumeration.
- [Wappalyzer](https://www.wappalyzer.com/) - Identify technologies behind websites.
- [OWASP ZAP](https://www.zaproxy.org/) - Web application vulnerability scanner.

### **Techniques**
- Directory brute-forcing (e.g., `gobuster`, `ffuf`).
- Analyzing and tampering cookies/session tokens.
- Exploring hidden forms or input validation issues.

---

## Binary Exploitation

### **Tools**
- [Ghidra](https://ghidra-sre.org/) - Reverse engineering suite.
- [IDA Free](https://hex-rays.com/ida-free/) - Disassembler for binary analysis.
- [pwndbg](https://github.com/pwndbg/pwndbg) - Debugging plugin for GDB.
- [PwnTools](https://github.com/Gallopsled/pwntools) - Python library for writing exploits.

### **Techniques**
- Stack smashing to overwrite return addresses.
- Exploiting buffer overflows.
- Using ROP chains for bypassing mitigations.

---

## Reverse Engineering

### **Tools**
- [radare2](https://github.com/radareorg/radare2) - Open-source reverse engineering framework.
- [Binary Ninja](https://binary.ninja/) - For analyzing binaries.
- [Frida](https://frida.re/) - Dynamic instrumentation toolkit.

### **Techniques**
- Static and dynamic analysis.
- Identifying encryption functions.
- Recognizing common patterns in compiled code.

---

## Forensics

### **Tools**
- [Autopsy](https://www.autopsy.com/) - GUI-based forensic tool.
- [Volatility](https://www.volatilityfoundation.org/) - Memory forensics framework.
- [binwalk](https://github.com/ReFirmLabs/binwalk) - Extract files hidden in images/binaries.
- [Wireshark](https://www.wireshark.org/) - Network traffic analysis.

### **Techniques**
- Extracting hidden data from images.
- Analyzing metadata in documents/media.
- Investigating network packet dumps.

---

## General Purpose Tools

- [nmap](https://nmap.org/) - Network scanning and enumeration.
- [netcat (nc)](https://man7.org/linux/man-pages/man1/nc.1.html) - For port scanning and reverse shells.
- [tmux](https://github.com/tmux/tmux/wiki) - Terminal multiplexer.
- [Python](https://www.python.org/) - Writing quick scripts for custom exploits.

---

## Practice Platforms

- [Hack The Box](https://www.hackthebox.com/)
- [PicoCTF](https://picoctf.org/)
- [TryHackMe](https://tryhackme.com/)
- [OverTheWire](https://overthewire.org/)
- [RingZer0](https://ringzer0ctf.com/)
- [Root-Me](https://www.root-me.org/)

---

## CTF Writeups & Resources

- [CTFTime](https://ctftime.org/) - Lists CTF events and writeups.
- [0xRick's Blog](https://0xrick.github.io/)
- [LiveOverflow YouTube](https://www.youtube.com/c/LiveOverflow) - CTF challenges explained.
- [Awesome CTF (GitHub)](https://github.com/apsdehal/awesome-ctf) - Extensive list of CTF resources.

---

## Miscellaneous

- [Malwoverview](https://github.com/alexandreborges/malwoverview) - Malware analysis tool.
- [Katana](https://github.com/JohnHammond/katana) - Automatic CTF Challenge Solver.
- [StegSolve](https://github.com/zardus/ctf-tools/tree/master/stegsolve) - Detect and analyze steganography.

---

Happy hacking! 🚀
