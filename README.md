# Hi, I'm Pouria

**Licensed mechanical engineer (P.Eng) who moved into IT. Finishing a Computer Science degree in Toronto.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pouria--abtahi-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pouria-abtahi)
![Location](https://img.shields.io/badge/Toronto-Canada-555?logo=googlemaps&logoColor=white)
![P.Eng](https://img.shields.io/badge/P.Eng-Ontario-7A1F2B)
![CompTIA A+](https://img.shields.io/badge/CompTIA-A%2B-C8202F)
![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B-C8202F)
![CompTIA Security+](https://img.shields.io/badge/Security%2B-in%20progress-lightgrey)

I spent three and a half years inspecting piping, tanks and pressure equipment as a mechanical engineer. Then I started again in Canada. I finished Computer Engineering Technology at Seneca with a 4.0 GPA. I spent two and a half years at TroxWeb in Toronto fixing laptops, phones, printers and Wi-Fi problems for walk-in customers. I also did a co-op supporting Seneca's networking and systems labs.

Today I work on networks, servers and security labs, firmware in C, and websites for real clients. Coming from engineering, I write things down, check my work, and follow a problem until I find what is actually causing it.

**Looking for:** IT support, infrastructure and cybersecurity roles in the GTA, including internships and co-ops.

## Right now

- 🎓 Bachelor of Computer Science at Algoma University, finishing May 2027
- 🔐 Studying for CompTIA Security+ (SY0-701), after A+ and Network+
- 🌐 Maintaining the four client websites below

## Client work

These are live sites for real businesses. The code is in private repositories, so the links go to the sites themselves.

| Client | What I built or do |
|---|---|
| [**Haniyeh Educational Complex**](https://www.haniyehschool.ir) | Bilingual Persian/English school website with separate campus sections. Staff use an admin panel to manage news, the gallery, photos and videos, campuses, staff and FAQs. Next.js, TypeScript, Tailwind CSS, Drizzle ORM, Neon Postgres, Vercel Blob. |
| **SEENCO Financial Services** | Public website with lead-capture forms, plus a sign-in portal for advisors and admins: role-based access, deal submission and admin review, contracting, payouts and reports. Next.js, TypeScript, NextAuth, Prisma, Resend. |
| [**CaninC**](https://www.caninc.org) | Website for an IT services company. Next.js, React, TypeScript and Tailwind CSS. |
| [**ABT Electric**](https://abtelectric.ca) | Toronto electrical contractor. Service pages, navigation and internal links, contact forms, deployment checks and production QA. |

## Embedded and hardware

All four come from my Computer Engineering Technology program at Seneca.

| Project | What it shows |
|---|---|
| [**freertos-emergency-shutdown-k64f**](https://github.com/pouria-abtahi/freertos-emergency-shutdown-k64f) | FreeRTOS firmware on an NXP Cortex-M4F: two tasks and a software timer synced by semaphores, with GPIO interrupts for emergency shutdown and a PIT interrupt for the alarm LED. CMake build and GitHub Actions CI. *(Fall 2024)* |
| [**advanced-iot-weather-station**](https://github.com/pouria-abtahi/advanced-iot-weather-station) | Raspberry Pi weather station in Python: temperature, humidity, rain and wind sensors over an SPI ADC, an LCD, GSM/SMS alerts for severe weather, a Blynk dashboard and a custom PCB. Team project. *(Fall 2024)* |
| [**variable-dc-power-supply-lm317**](https://github.com/pouria-abtahi/variable-dc-power-supply-lm317) | Mains-powered bench supply, adjustable from about 2 V to 14 V, built around an LM317. Single-sided PCB in PADS, Gerbers, BOM, enclosure, and Hi-Pot and insulation-resistance safety tests. Team project. *(Winter 2024)* |
| [**labjack-servo-capacitor-control**](https://github.com/pouria-abtahi/labjack-servo-capacitor-control) | A C program on a LabJack U3-HV reads a capacitor's voltage and drives a servo (50 Hz PWM) and an LED when it crosses a set threshold. Includes the PCB I designed for it. *(Winter 2023)* |

## Software

| Project | What it is |
|---|---|
| [**client-server-shopping-system**](https://github.com/pouria-abtahi/client-server-shopping-system) | C# client and server that talk over TCP with a custom command protocol. Supports multiple clients, logins, inventory and orders. |
| [**airline-reservation-system**](https://github.com/pouria-abtahi/airline-reservation-system) | C# Windows Forms app on SQLite: flight search, purchases, receipts. |
| [**basketvr-toss-vr-game**](https://github.com/pouria-abtahi/basketvr-toss-vr-game) | Unity VR basketball game with grab-and-throw physics and scoring. Team project, I was the developer. |

## Infrastructure and security labs

All of these ran on virtual machines for my Seneca courses.

| Lab | What it shows |
|---|---|
| [**security-incident-simulation-lab**](https://github.com/pouria-abtahi/security-incident-simulation-lab) | Attacker and defender in one lab: Nessus scans (20 critical findings on Metasploitable 3), a Covenant C2 compromise of Windows 10 by phishing, then detection in Security Onion and cleanup. Team of two. *(Summer 2024)* |
| [**linux-network-services-lab**](https://github.com/pouria-abtahi/linux-network-services-lab) | Fedora server and client: DHCP, BIND DNS, NFS, Samba, mail, Apache and Roundcube, CUPS, VNC over SSH, and a firewalld gateway with NAT. Configs and screenshots. *(Winter 2024)* |

Not on GitHub, because I don't have the files anymore:

- **Active Directory domain:** multi-VM setup with a domain controller, OUs and security groups. Group Policy for password policy, account lockout, USB restriction and drive mapping.
- **Small-office network services:** Windows Server with DHCP scopes, forward and reverse DNS zones, internal IIS sites and Defender Firewall rules.
- **Packet analysis:** Wireshark captures matched against ipconfig, nslookup, tracert and netstat output.

## Toolbox

[![Skills](https://skillicons.dev/icons?i=c,cpp,cs,py,java,ts,js,nextjs,react,tailwind,prisma,postgres,sqlite,vercel,windows,linux,kali,powershell,bash,git,githubactions,raspberrypi,cmake,unity,azure&perline=13)](https://skillicons.dev)

- **Languages:** C · C++ · C# · Python · Java · TypeScript / JavaScript · SQL · PowerShell · Bash
- **Systems and networking:** Windows Server 2022 · Active Directory and Group Policy · DHCP, DNS, IIS · Linux (Fedora, Kali) · TCP/IP, VLANs, subnetting · Cisco · VMware, VirtualBox
- **Security (lab):** Wireshark · Nmap · Nessus · Metasploit · Aircrack-ng · John the Ripper · Microsoft Defender
- **Web:** Next.js · React · Tailwind CSS · NextAuth · Prisma and Drizzle ORM · PostgreSQL (Neon) · Vercel
- **Embedded and hardware:** FreeRTOS · ARM Cortex-M4F (NXP Kinetis) · MCUXpresso · Raspberry Pi · LabJack · PADS · Proteus
- **AI tools:** Claude Code and Codex, set up with `CLAUDE.md` project files, skills and MCP servers

## Background

- **P.Eng, Mechanical Engineering**, Professional Engineers Ontario (2026). M.Sc. and B.Sc. in Mechanical Engineering, Shiraz University
- **Advanced Diploma, Computer Engineering Technology**, Seneca Polytechnic (2024): 4.0 GPA, High Honours, President's Honour List for five terms in a row
- **Bachelor of Computer Science**, Algoma University, expected May 2027
- **CompTIA** A+, Network+ and IT Operations Specialist. Security+ in progress
- English (professional working) and Persian (native)

## Get in touch

The fastest way to reach me is on [LinkedIn](https://www.linkedin.com/in/pouria-abtahi). I'm happy to talk about roles, a project, or anything in this README.
