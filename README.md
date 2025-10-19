Cyber Internship — Task 1 
Foundation & Environment Setup - 

 Overview
This repo contains my deliverables for **Task 1: Foundation & Environment Setup** of my cybersecurity internship. It includes lab setup notes, commands, screenshots, and a short walkthrough video.

Folder structure
inside the Task 1 folder 

/notes
/commands
/screenshots
/videos
README.md


 How to reproduce (quick)
1. Install VirtualBox (or VMware).
2. Import/create two VMs:
   - `kali-attacker` (Kali Linux)
   - `target-victim` (Metasploitable2 or DVWA)
3. Configure both VMs to use the same Host-only Adapter network.
4. From `kali-attacker`, run the scripts in `/commands` to reproduce basic actions.

 Important files
- `/notes/basics.md` — CIA triad, threat types
- `/notes/lab_setup.md` — network & VM IPs
- `/notes/linux_cheatsheet.md` — Linux commands used
- `/notes/crypto.md` — openSSL steps
- `/notes/networking.md` — nmap & subnetting notes
- `/commands` — small runnable scripts (see below)
- `/screenshots` — images of setup and outputs
- `/videos/walkthrough.mp4` — 5-min recorded demo

 Safety & scope
All tests and scans were performed ONLY in an isolated lab environment (Host-only network). No scanning or attacks were performed on public networks or external systems.

 Contact / Notes
If reviewer needs different outputs (more screenshots, different scans, or extra explanations), ask and I will provide.
