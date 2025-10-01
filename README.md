# 🏴 Road To CTF – Beginner’s Guide  

## 📌 What are CTFs?  

**Capture The Flag (CTF)** competitions are cybersecurity challenges where participants find hidden “flags” (strings or tokens) by solving puzzles in areas like:  

- 🔐 **Cryptography**  
- 🔎 **Forensics & Steganography**  
- 🌎 **Web Exploitation**  
- ⚙️ **Binary Exploitation (pwn)**  
- 🔄 **Reverse Engineering**  
- 🕵️ **OSINT**  
- ❓ **Miscellaneous challenges**  
### 🆕 Emerging Categories 
- 🕵️ **LLM**
- 🕵️ **BlockChain**

There are **two main types of CTFs**:  

1. **[Jeopardy-Style](https://rohit12.medium.com/how-i-solve-jeopardy-style-ctf-challenges-to-exploit-security-vulnerabilities-to-find-the-flags-and-b3a497ddbf22)** – Solve independent tasks across categories for points. Great for beginners.  
2. **[Attack-Defense](https://medium.com/@iabdullah_215/my-guide-to-attack-and-defense-ctfs-ecbe838d49cd)** – Teams defend their own servers while attacking others. More advanced and team-oriented.  

---

## 🛠 Prerequisites  

Before diving in, it helps to know:  

- 🖥 Basics of **Computer Systems** & **Linux Command Line**  
- 🧑‍💻 **Programming** ([C](https://en.wikipedia.org/wiki/C_(programming_language)), [C++](https://en.wikipedia.org/wiki/C%2B%2B), [Python](https://www.python.org/))  
- 🌐 **Networking** & Security Fundamentals  
- 🔐 Basics of **Cryptography** ([Encryption](https://www.digitalguardian.com/blog/what-data-encryption), [Hashing](https://www.codecademy.com/resources/blog/what-is-hashing))  
- 📊 **Data formats** (Binary, Hexadecimal, ASCII, hexdumps)  

> Don’t worry if you don’t know all of this yet — CTFs are a way to learn by doing!  

---

## 🎯 Where to Start  

### Beginner-Friendly Platforms  
- 🎮 [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) – Linux basics through fun levels.  
🕵️ [RootMe](https://www.root-me.org/) – Large collection of challenges across categories (web, crypto, reverse, forensics). 
- 🌍 [CTFlearn](https://ctflearn.com/) – Community-driven CTF site with many beginner-level challenges. 
- 🔐 [CryptoHack](https://cryptohack.org/) – Very popular for practicing cryptography challenges.  
- 📚 [W3Challs](https://w3challs.com/) – Widely used training ground for web exploitation, crypto, and reversing.  
- 🏴 [picoCTF](https://picoctf.org/) – Beginner CTF platform with hints and practice challenges.  
- 📘 [CTF101 Handbook](https://ctf101.org/) – Essential theory and techniques.   

### Other Useful Platforms  
- [HackTheBox](https://www.hackthebox.com/) & HTB CTF events  
- [TryHackMe](https://tryhackme.com/) learning paths  
- [VulnHub](https://www.vulnhub.com/) practice machines  
- [HackThisSite](https://www.hackthissite.org/)  

---



## 📚 Learning Roadmap  

1. Learn **Linux basics** → [OverTheWire Bandit](https://overthewire.org/wargames/bandit/)  
2. Understand **Networking** → [Practical Networking](https://www.youtube.com/@PracticalNetworking),   [Network Chuck ](https://www.youtube.com/@NetworkChuck)
3. Start with **Web & Crypto challenges** → [youtube](https://www.youtube.com/watch?v=0jCGyf32rHs&list=PLHUKi1UlEgOIn12nvhwwq2aTU8bG-FE0I) 
4. Dive into **Reverse Engineering & Binary Exploitation** → [John Hammond](https://www.youtube.com/@_JohnHammond),  [LiveOverflow](https://www.youtube.com/c/LiveOverflow)  
5. Practice weekly on [CTFtime events](https://ctftime.org/),   [Htb Events](https://ctf.hackthebox.com/event)

---
## 🛠 Tools & Resources  

This section highlights the essential categories in CTFs along with the most commonly used tools and learning resources.  

---

### 🔑 Binary Exploitation (pwn)  
- 🛠 [pwntools](https://docs.pwntools.com/en/stable/) – Python library for exploit development  
- 🛠 [GDB](https://www.sourceware.org/gdb/) – GNU Debugger for analyzing binaries  
- 🛠 [GEF](https://github.com/hugsy/gef) – GDB Enhanced Features (plugin with shortcuts & visualization)  
- 🛠 [Pwndbg](https://github.com/pwndbg/pwndbg) – GDB plugin focused on exploit dev  
- 🛠 [radare2](https://rada.re/n/) – Reverse engineering framework with debugger support  

---

### 🔄 Reverse Engineering  
Analyzing compiled code to uncover logic and hidden functionality.  
- 🛠 [IDA Free](https://hex-rays.com/ida-free/)  
- 🛠 [Ghidra](https://ghidra-sre.org/)  
- 🛠 [Radare2](https://rada.re/n/)  

---

### 🌎 Web Exploitation  
Finding and exploiting vulnerabilities in web applications (SQLi, XSS, CSRF, etc.).   
- 🛠 [SQLMap](http://sqlmap.org/)  
- 🛠 [feroxbuster](https://github.com/epi052/feroxbuster) – A fast, simple, recursive content discovery tool written in Rust
- 🛠 [gobuster](https://github.com/OJ/gobuster)  
  

---

### 🔐 Cryptography  
Breaking ciphers, cracking keys, and exploiting weak algorithms.  
- 📘 [Cryptopals](https://cryptopals.com/) -- practice here
- 🌐 [CryptoHack](https://cryptohack.org/)  -- practice here
- 🛠 [dCode.fr](https://www.dcode.fr/) – Cryptography solvers & decoders  

---

### 🔎 Forensics & Steganography  
Uncovering hidden data in files, memory dumps, and network traffic.  
- 🛠 [Wireshark](https://www.wireshark.org/)  
- 🛠 [Binwalk](https://github.com/ReFirmLabs/binwalk)  
- 🛠 [Stegsolve](https://github.com/zardus/ctf-tools/blob/master/stegsolve/install)  
- 🛠 [CyberChef](https://gchq.github.io/CyberChef/) – Universal data manipulation tool  

---

### 🕵️ OSINT (Open Source Intelligence)  
Finding information from open and public sources.  
- 🌐 [Google Dorks](https://www.group-ib.com/resources/knowledge-hub/google-dorks/)  
- 🌐 [Google Reverse Image Search](https://images.google.com/)  
- 🌐 [Archive.org](https://archive.org/)  

---
## Important repos
- 📜 [PayloadAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) – Huge repo of exploits & payloads  
-  [RPISEC](https://github.com/RPISEC) -- teaching & research materials related to security, binary exploitation, malware
- 📘 [PortSwigger Web Security Academy](https://portswigger.net/web-security) 