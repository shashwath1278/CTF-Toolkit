
# 🔐 CTF Cheat Sheet

## **Cryptography**
### **Hash Cracking**
```bash
john --wordlist=rockyou.txt hash.txt
hashcat -m 0 hash.txt rockyou.txt
```
### **Base Encodings**
```bash
echo "SGVsbG8=" | base64 -d  # Decode base64
echo -n "Hello" | base64     # Encode base64
```
### **RSA Decryption**
```bash
python3 RsaCtfTool.py --publickey key.pub --attack all
```
### **Factorizing n (RSA)**
```bash
curl "http://factordb.com/api?query=<n>"
```
### **Cipher Challenges**
```bash
caesar_cipher.py "KHOOR"  # Shift Cipher (Caesar)
python3 vigenere.py decrypt "ciphertext" "key"
python3 xor_decoder.py "ciphertext" "key"
```

## **🛠️ Source Code Analysis**
### **Quick Search for Vulnerabilities**
```bash
grep -Ri "password\|secret\|key" .
rg "password|secret|key"
semgrep --config auto .  # Auto-detect security issues
```
### **Extract Strings from Binary**
```bash
strings binaryfile
```
### **Beautify Minified Code**
```bash
js-beautify script.js -o output.js
php -d auto_prepend_file='' -r 'echo highlight_file("script.php", true);'
```

## **🌐 Subdomain & Directory Discovery**
### **Find Directories**
```bash
gobuster dir -u http://example.com -w common.txt
ffuf -u http://example.com/FUZZ -w wordlist.txt
```
### **Wayback Machine URL Discovery**
```bash
waybackurls example.com
gau example.com | tee urls.txt
```
### **Find Subdomains**
```bash
subfinder -d example.com
```
### **Check Open Ports**
```bash
nmap -p- example.com
```

## **🖼️ Steganography**
### **Extract Hidden Data**
```bash
steghide extract -sf image.jpg
```
### **Analyze PNG/BMP for Hidden Data**
```bash
zsteg image.png
```
### **Extract Metadata**
```bash
exiftool image.jpg
```
### **Extract Hidden Files in Images**
```bash
binwalk -e image.png
```
### **Analyze Image Layers**
```bash
java -jar stegsolve.jar
```
```
