# Information comes from [carpedm20/awesome-hacking](https://github.com/carpedm20/awesome-hacking)
# Awesome Hacking [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Hacking. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning/)

If you want to contribute to this list (please do), send me a pull request or contact me [@carpedm20](https://twitter.com/carpedm20)

For a list of free hacking books available for download, go [here](https://github.com/Hack-with-Github/Free-Security-eBooks)


## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [System](#system)
    - [Tutorials](#tutorials)
    - [Tools](#tools)
    - [Docker](#docker-images-for-penetration-testing--security)
    - [General](#general)
- [Reverse Engineering](#reverse-engineering)
    - [Tutorials](#tutorials-1)
    - [Tools](#tools-1)
    - [General](#general-1)
- [Web](#web)
    - [Tools](#tools-2)
    - [General](#general-2)
- [Network](#network)
    - [Tools](#tools-3)
- [Forensic](#forensic)
    - [Tools](#tools-4)
- [Cryptography](#cryptography)
    - [Tools](#tools-5)
- [Wargame](#wargame)
    - [System](#system-1)
    - [Reverse Engineering](#reverse-engineering-1)
    - [Web](#web-1)
    - [Cryptography](#cryptography-1)
    - [Bug bounty](#bug-bounty)
- [CTF](#ctf)
    - [Competition](#competition)
    - [General](#general-2)
- [OS](#os)
    - [Online resources](#online-resources)
- [Post exploitation](#post-exploitation)
    - [tools](#tools-6)
- [ETC](#etc)

<!-- /MarkdownTOC -->

# System

## Tutorials
 * [Corelan Team's Exploit writing tutorial](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
 * [Exploit Writing Tutorials for Pentesters](http://www.punter-infosec.com/exploit-writing-tutorials-for-pentesters/)
 * [Understanding the basics of Linux Binary Exploitation](https://github.com/r0hi7/BinExp) :star:411

## Tools
 * [Metasploit](https://github.com/rapid7/metasploit-framework) A computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development.
 * [mimikatz](https://github.com/gentilkiwi/mimikatz) - A little tool to play with Windows security :star:8137

### Docker Images for Penetration Testing & Security
 * `docker pull kalilinux/kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/)
 * `docker pull owasp/zap2docker-stable` - [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
 * `docker pull wpscanteam/wpscan` - [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
 * `docker pull pandrew/metasploit` - [docker-metasploit](https://hub.docker.com/r/pandrew/metasploit/)
 * `docker pull citizenstig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
 * `docker pull wpscanteam/vulnerablewordpress` - [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
 * `docker pull hmlio/vaas-cve-2014-6271` - [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
 * `docker pull hmlio/vaas-cve-2014-0160` - [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
 * `docker pull opendns/security-ninjas` - [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
 * `docker pull usertaken/archlinux-pentest-lxde` - [Arch Linux Penetration Tester](https://hub.docker.com/r/usertaken/archlinux-pentest-lxde/)
 * `docker pull diogomonica/docker-bench-security` - [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
 * `docker pull ismisepaul/securityshepherd` - [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
 * `docker pull danmx/docker-owasp-webgoat` - [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
 * `docker-compose build && docker-compose up` - [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
 * `docker pull citizenstig/nowasp` - [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
 * `docker pull bkimminich/juice-shop` - [OWASP Juice Shop](https://github.com/bkimminich/juice-shop#docker-container--)

## General
 * [Exploit database](https://www.exploit-db.com/) - An ultimate archive of exploits and vulnerable software


# Reverse Engineering

## Tutorials
* [Lenas Reversing for Newbies](https://tuts4you.com/download.php?list.17)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](http://fumalwareanalysis.blogspot.kr/p/malware-analysis-tutorials-reverse.html)

## Tools
### Disassemblers and debuggers
 * [IDA](https://www.hex-rays.com/products/ida/) - IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger
 * [OllyDbg](http://www.ollydbg.de/) - A 32-bit assembler level analysing debugger for Windows
 * [x64dbg](https://github.com/x64dbg/x64dbg) - An open-source x64/x32 debugger for Windows :star:34117
 * [radare2](https://github.com/radare/radare2) - A portable reversing framework :star:10751
 * [plasma](https://github.com/joelpx/plasma) - Interactive disassembler for x86/ARM/MIPS. Generates indented pseudo-code with colored syntax code. :star:2780
 * [ScratchABit](https://github.com/pfalcon/ScratchABit) - Easily retargetable and hackable interactive disassembler with IDAPython-compatible plugin API :star:318
 * [Capstone](https://github.com/aquynh/capstone) :star:3701

### Decompilers
*  JVM-based languages
  * [Krakatau](https://github.com/Storyyeller/Krakatau) - the best decompiler I have used. Is able to decompile apps written in Scala and Kotlin into Java code. JD-GUI and Luyten have failed to do it fully. :star:1037
  * [JD-GUI](https://github.com/java-decompiler/jd-gui) 
  * [procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler)
    * [Luyten](https://github.com/deathmarine/Luyten) - one of the best, though a bit slow, hangs on some binaries and not very well maintained. :star:2825
  * [JAD](http://varaneckas.com/jad/) - JAD Java Decompiler (closed-source, unmaintained)
  * [JADX](https://github.com/skylot/jadx) - a decompiler for Android apps. Not related to JAD. :star:19554

* .net-based languages
  * [dotPeek](https://www.jetbrains.com/decompiler/) - a free-of-charge .NET decompiler from JetBrains
  * [ILSpy](https://github.com/icsharpcode/ILSpy/) - an open-source .NET assembly browser and decompiler :star:8305
  * [dnSpy](https://github.com/0xd4d/dnSpy) - .NET assembly editor, decompiler, and debugger :star:11197

* native code
  * [Hopper](https://www.hopperapp.com) - A OS X and Linux Disassembler/Decompiler for 32/64-bit Windows/Mac/Linux/iOS executables.
  * [cutter](https://github.com/radareorg/cutter) - a decompiler based on radare2. :star:5366
  * [retdec](https://github.com/avast-tl/retdec) :star:4907
  * [snowman](https://github.com/yegord/snowman) :star:1607
  * [Hex-Rays](https://www.hex-rays.com/products/decompiler/)

### Deobfuscators
 * [de4dot](https://github.com/0xd4d/de4dot) - .NET deobfuscator and unpacker. :star:3342
 * [JS Beautifier](https://github.com/beautify-web/js-beautify) :star:6341
 * [JS Nice](http://jsnice.org/) - a web service guessing JS variables names and types based on the model derived from open source.

### Other
 * [nudge4j](https://github.com/lorenzoongithub/nudge4j) - Java tool to let the browser talk to the JVM :star:137
 * [dex2jar](https://github.com/pxb1988/dex2jar) - Tools to work with Android .dex and Java .class files :star:6465
 * [androguard](https://code.google.com/p/androguard/) - Reverse engineering, malware and goodware analysis of Android applications
 * [antinet](https://github.com/0xd4d/antinet) - .NET anti-managed debugger and anti-profiler code :star:188
 * [UPX](http://upx.sourceforge.net/) - the Ultimate Packer (and unpacker) for eXecutables

### Execution logging and tracing
 * [Wireshark](https://www.wireshark.org/) - A free and open-source packet analyzer
 * [tcpdump](http://www.tcpdump.org/) - A powerful command-line packet analyzer; and libpcap, a portable C/C++ library for network traffic capture
 * [mitmproxy](https://github.com/mitmproxy/mitmproxy) - An interactive, SSL-capable man-in-the-middle proxy for HTTP with a console interface :star:15906
 * [Charles Proxy](https://charlesproxy.com) - A cross-platform GUI web debugging proxy to view intercepted HTTP and HTTPS/SSL live traffic
 * [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) - USB capture for Linux.
 * [USBPcap](https://github.com/desowin/usbpcap) - USB capture for Windows. :star:387
 * [dynStruct](https://github.com/ampotos/dynStruct) - structures recovery via dynamic instrumentation. :star:205
 * [drltrace](https://github.com/mxmssh/drltrace) - shared library calls tracing. :star:180

### Binary files examination and editing

#### Hex editors
 * [HxD](http://mh-nexus.de/en/hxd/) - A hex editor which, additionally to raw disk editing and modifying of main memory (RAM), handles files of any size
 * [WinHex](http://www.winhex.com/winhex/) - A hexadecimal editor, helpful in the realm of computer forensics, data recovery, low-level data processing, and IT security
* [wxHexEditor](https://github.com/EUA/wxHexEditor) :star:238
* [Synalize It](https://www.synalysis.net/)/[Hexinator](https://hexinator.com/) - 

#### Other
 * [Binwalk](https://github.com/ReFirmLabs/binwalk) -  Detects signatures, unpacks archives, visualizes entropy. :star:4781
 * [Veles](https://github.com/codilime/veles) - a visualizer for statistical properties of blobs. :star:590
 * [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct) - a DSL for creating parsers in a variety of programming languages. The Web IDE is particulary useful fir reverse-engineering. :star:1631
 * [Protobuf inspector](https://github.com/jmendeth/protobuf-inspector) :star:271
 * [DarunGrim](https://github.com/ohjeongwook/DarunGrim) - executable differ. :star:294
 * [DBeaver](https://github.com/dbeaver/dbeaver) - a DB editor. :star:9934
 * [Dependencies](https://github.com/lucasg/Dependencies) - a FOSS replacement to Dependency Walker. :star:1517
 * [PEview](http://wjradburn.com/software/) - A quick and easy way to view the structure and content of 32-bit Portable Executable (PE) and Component Object File Format (COFF) files
* [BinText](https://web.archive.org/web/http://www.mcafee.com/kr/downloads/free-tools/bintext.aspx) - A small, very fast and powerful text extractor that will be of particular interest to programmers.

## General
 * [Open Malware](http://www.offensivecomputing.net/)

# Web

## Tools
 * [sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool :star:14845
 * [NoSQLMap](https://github.com/codingo/NoSQLMap) - Automated NoSQL database enumeration and web application exploitation tool. :star:1096
 * [tools.web-max.ca](http://tools.web-max.ca/encode_decode.php) - base64 base85 md4,5 hash, sha1 hash encoding/decoding
 * [VHostScan](https://github.com/codingo/VHostScan) - A virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, aliases and dynamic default pages. :star:510
 * [SubFinder](https://github.com/subfinder/subfinder) - SubFinder is a subdomain discovery tool that discovers valid subdomains for any target using passive online sources. :star:1489
 * [badtouch](https://github.com/kpcyrd/badtouch) - Scriptable network authentication cracker :star:174

## General
 * [Strong node.js](https://github.com/jesusprubio/strong-node) - An exhaustive checklist to assist in the source code security analysis of a node.js web service. :star:212


# Network

## Tools
 * [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - A Network Forensic Analysis Tool (NFAT)
 * [Paros](http://sourceforge.net/projects/paros/) - A Java-based HTTP/HTTPS proxy for assessing web application vulnerability
 * [pig](https://github.com/rafael-santiago/pig) - A Linux packet crafting tool :star:354
 * [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - The Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications
 * [mitmsocks4j](https://github.com/Akdeniz/mitmsocks4j) - Man-in-the-middle SOCKS Proxy for Java :star:24
 * [ssh-mitm](https://github.com/jtesta/ssh-mitm) - An SSH/SFTP man-in-the-middle tool that logs interactive sessions and passwords. :star:1155
 * [nmap](https://nmap.org/) - Nmap (Network Mapper) is a security scanner
 * [Aircrack-ng](http://www.aircrack-ng.org/) - An 802.11 WEP and WPA-PSK keys cracking program
 * [Nipe](https://github.com/GouveaHeitor/nipe) - A script to make Tor Network your default gateway. :star:620
 * [Habu](https://github.com/portantier/habu) - Python Network Hacking Toolkit :star:414
 * [Wifi Jammer](https://n0where.net/wifijammer/) - Free program to jam all wifi clients in range
 * [Firesheep](https://codebutler.github.io/firesheep/) - Free program for HTTP session hijacking attacks.
 * [Scapy](https://github.com/secdev/scapy) - A Python tool and library for low level packet creation and manipulation :star:4190
 * [Amass](https://github.com/OWASP/Amass) - In-depth subdomain enumeration tool that performs scraping, recursive brute forcing, crawling of web archives, name altering and reverse DNS sweeping :star:1636
 * [sniffglue](https://github.com/kpcyrd/sniffglue) - Secure multithreaded packet sniffer :star:370


# Forensic

## Tools
 * [Autopsy](http://www.sleuthkit.org/autopsy/) - A digital forensics platform and graphical interface to [The Sleuth Kit](http://www.sleuthkit.org/sleuthkit/index.php) and other digital forensics tools
 * [sleuthkit](https://github.com/sleuthkit/sleuthkit) - A library and collection of command-line digital forensics tools :star:1408
 * [EnCase](https://www.guidancesoftware.com/products/Pages/encase-forensic/overview.aspx) - The shared technology within a suite of digital investigations products by Guidance Software
 * [malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool

# Cryptography

### Tools
 * [xortool](https://github.com/hellman/xortool) - A tool to analyze multi-byte XOR cipher :star:744
 * [John the Ripper](http://www.openwall.com/john/) - A fast password cracker
 * [Aircrack](http://www.aircrack-ng.org/) - Aircrack is 802.11 WEP and WPA-PSK keys cracking program.


# Wargame

## System
 * [OverTheWire - Semtex](http://overthewire.org/wargames/semtex/)
 * [OverTheWire - Vortex](http://overthewire.org/wargames/vortex/)
 * [OverTheWire - Drifter](http://overthewire.org/wargames/drifter/)
 * [pwnable.kr](http://pwnable.kr/) - Provide various pwn challenges regarding system security
 * [Exploit Exercises - Nebula](https://exploit-exercises.com/nebula/)
 * [SmashTheStack](http://smashthestack.org/)

## Reverse Engineering
 * [Reversing.kr](http://www.reversing.kr/) - This site tests your ability to Cracking & Reverse Code Engineering
 * [CodeEngn](http://codeengn.com/challenges/) - (Korean)
 * [simples.kr](http://simples.kr/) - (Korean)
 * [Crackmes.de](http://crackmes.de/) - The world first and largest community website for crackmes and reversemes.

## Web
 * [Hack This Site!](https://www.hackthissite.org/) - a free, safe and legal training ground for hackers to test and expand their hacking skills
 * [Hack The Box](https://www.hackthebox.eu) - a free site to perform pentesting in a variety of different systems.
 * [Webhacking.kr](http://webhacking.kr/)
 * [0xf.at](https://0xf.at/) - a website without logins or ads where you can solve password-riddles (so called hackits).
 * [Gruyere](https://google-gruyere.appspot.com/)
 * [Others](https://www.owasp.org/index.php/OWASP_Vulnerable_Web_Applications_Directory_Project#tab=On-Line_apps)

## Cryptography
 * [OverTheWire - Krypton](http://overthewire.org/wargames/krypton/)

## Bug bounty
  * [Awesome bug bounty resources by EdOverflow](https://github.com/EdOverflow/bugbounty-cheatsheet) :star:1776
  
## Bug bounty -  Earn Some Money  
  * [Bugcrowd](https://www.bugcrowd.com/)
  * [Hackerone](https://www.hackerone.com/start-hacking)
  

# CTF

## Competition
 * [DEF CON](https://legitbs.net/)
 * [CSAW CTF](https://ctf.isis.poly.edu/)
 * [hack.lu CTF](http://hack.lu/)
 * [Pliad CTF](http://www.plaidctf.com/)
 * [RuCTFe](http://ructf.org/e/)
 * [Ghost in the Shellcode](http://ghostintheshellcode.com/)
 * [PHD CTF](http://www.phdays.com/)
 * [SECUINSIDE CTF](http://secuinside.com/)
 * [Codegate CTF](http://ctf.codegate.org/html/Main.html?lang=eng)
 * [Boston Key Party CTF](http://bostonkeyparty.net/)
 * [ZeroDays CTF](https://zerodays.ie/)
 * [Insomni’hack](https://insomnihack.ch/)
 * [Pico CTF](https://picoctf.com/) 
 * [prompt(1) to win](http://prompt.ml/) - XSS Challeges

## General
 * [Hack+](http://hack.plus) - An Intelligent network of bots that fetch the latest InfoSec content.
 * [CTFtime.org](https://ctftime.org/) - All about CTF (Capture The Flag)
 * [WeChall](http://www.wechall.net/)
 * [CTF archives (shell-storm)](http://shell-storm.org/repo/CTF/)
 * [Rookit Arsenal](https://amzn.com/144962636X) - OS RE and rootkit development
 * [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - Collection of cheat sheets useful for pentesting :star:1554
 * [Movies For Hackers](https://github.com/k4m4/movies-for-hackers) - A curated list of movies every hacker & cyberpunk must watch. :star:7601

# OS

## Online resources
 * [Security related Operating Systems @ Rawsec](http://rawsec.ml/en/security-related-os/) - Complete list of security related operating systems
 * [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) - Description of main penetration testing distributions
 * [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - Website dedicated to talking about, reviewing and keeping up to date with open source operating systems
# Post exploitation

## tools
* [empire](https://github.com/EmpireProject/Empire) - A post exploitation framework for powershell and python. :star:4705
* [silenttrinity](https://github.com/byt3bl33d3r/SILENTTRINITY) - A post exploitation tool that uses iron python to get past powershell restrictions. :star:802

# ETC
 * [SecTools](http://sectools.org/) - Top 125 Network Security Tools

