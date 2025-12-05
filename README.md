# HackingTool

## Description

HackingTool is an all-in-one hacking/penetration-testing toolkit built as a unified command-line interface, aggregating multiple tools and modules for information gathering, web and network reconnaissance, and other pen-testing tasks.  

This project aims to provide a single, easy-to-use framework to run a variety of security tools — similar in spirit to frameworks like Metasploit — but grouping many common utilities in one place. It supports multiple platforms including Linux (and distributions like Kali), Windows, and Android/Termux. :contentReference[oaicite:2]{index=2}

## Features

- 🔍 **Information gathering** — domain/website reconnaissance, OSINT, scanning. :contentReference[oaicite:3]{index=3}  
- 🌐 **Web & network attacks** — SQL injection, XSS, web vulnerability scanning, etc. :contentReference[oaicite:4]{index=4}  
- 🎯 **Payload generation & exploitation tools** — malware generation, RATs, reverse-engineering utilities. :contentReference[oaicite:5]{index=5}  
- 🛠️ **Forensics & extra utilities** — hash crackers, wordlist tools, crawlers, steganography, and more. :contentReference[oaicite:6]{index=6}  
- 📱 **Cross-platform support** — usable on Linux, Windows, and Android/Termux. :contentReference[oaicite:7]{index=7}

## Prerequisites

- A Unix-like environment (Linux, Termux on Android, or Windows with WSL / compatible shell)  
- **Bash** and **Python** installed (version as required by bundled tools) :contentReference[oaicite:8]{index=8}  
- Optional: root/sudo privileges (for certain tools)  

## Installation

```bash
git clone https://github.com/mohammad-arch-svg/HackingTool
cd HackingTool
chmod -R ethical.sh
 bash ethical.sh
