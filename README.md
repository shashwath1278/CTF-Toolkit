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
- [quipquip](https://quipqiup.com/) - Frequency analysis and automatic cipher solving.
- [ROT13](https://rot13.com/) - Simple ROT13 encoding and decoding tool.
- [Katana](https://github.com/JohnHammond/katana) - Automatic CTF Challenge Solver in Python3

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
- [HTTPie](https://httpie.io/) - User-friendly cURL alternative for HTTP requests.

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
- [gef](https://github.com/hugsy/gef) - GDB enhanced features.
- [one_gadget](https://github.com/david942j/one_gadget) - ROP chain generator.
- [ROPgadget](https://github.com/JonathanSalwan/ROPgadget) - Find ROP gadgets.
- [PwnTools](https://github.com/Gallopsled/pwntools) - Python library for writing exploits.

### **Techniques**
- Stack smashing to overwrite return addresses.
- Exploiting buffer overflows (stack/heap-based).
- Using ROP chains for bypassing mitigations like ASLR.
- Identifying function pointers in GOT/PLT.

---

## Reverse Engineering

### **Tools**
- [radare2](https://github.com/radareorg/radare2) - Open-source reverse engineering framework.
- [Binary Ninja](https://binary.ninja/) - For analyzing binaries.
- [Objection](https://github.com/sensepost/objection) - Mobile app (Android/iOS) reversing.
- [Frida](https://frida.re/) - Dynamic instrumentation toolkit.
- [strings](https://man7.org/linux/man-pages/man1/strings.1.html) - Extract readable text from binaries.
- [uncompyle6](https://github.com/rocky/python-uncompyle6) - Python bytecode decompiler.
- [apktool](https://ibotpeaches.github.io/Apktool/) - Android APK reverse engineering.

### **Techniques**
- Static analysis (disassembling binaries).
- Dynamic analysis with debuggers.
- Identifying encryption/decryption functions.
- Recognizing common patterns in compiled code.

---

## Forensics

### **Tools**
- [Autopsy](https://www.autopsy.com/) - GUI-based forensic tool.
- [Volatility](https://www.volatilityfoundation.org/) - Memory forensics framework.
- [binwalk](https://github.com/ReFirmLabs/binwalk) - Extract files hidden in images/binaries.
- [exiftool](https://exiftool.org/) - Metadata extraction from media files.
- [foremost](https://foremost.sourceforge.net/) - File recovery tool.
- [Wireshark](https://www.wireshark.org/) - Network traffic analysis.
- [StegSolve](https://github.com/zardus/ctf-tools/tree/master/stegsolve) - Detect and analyze steganography.

### **Techniques**
- Extracting hidden data from images (steganography).
- Analyzing metadata in documents/media.
- Investigating network packet dumps for sensitive data.

---

## General Purpose Tools

- [nmap](https://nmap.org/) - Network scanning and enumeration.
- [nc (netcat)](https://man7.org/linux/man-pages/man1/nc.1.html) - For port scanning, file transfers, and reverse shells.
- [tmux](https://github.com/tmux/tmux/wiki) - Terminal multiplexer to organize multiple tools.
- [Python](https://www.python.org/) - Writing quick scripts for custom exploits.
- [jq](https://stedolan.github.io/jq/) - Parse JSON data.
- [file](https://man7.org/linux/man-pages/man1/file.1.html) - Identify file type/magic numbers.
- [xxd](https://linux.die.net/man/1/xxd) - Hex dump tool.
- [nikito](https://github.com/sullo/nikto?tab=readme-ov-file) - Vuln scan tool.


---

Happy hacking! 🚀
