<div align="center"> 

![Header](./assets/header-banner.png) 
[[ <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/linkedin.svg" height="16" align="absmiddle" /> Linkedin ]](https://www.linkedin.com/in/pablo-andre-7b1138373)
[[ <img src="https://cdn.jsdelivr.net/gh/selfhst/icons/svg/mailflow-sh.svg" height="16" align="absmiddle" /> Email ]](mailto:pablo.andre-benito.etu@univ-lille.fr)

<img src="https://terminal-identity-opal.vercel.app/api?name=Pablo+Andre&username=karch00&role=CS+%26+Systems+student&tagline=Daring+to+apply&status=Available+for+anything%21&command=cargo+run+github-profile&theme=obsidian%2Fgraphite&avatar=KH&pattern=pulse&width=980&height=auto&accent=%23e0bc0e&showLangs=on&showContribs=on&stats=repos%2Cfollowers&excludeLangs=css%2Clua%2Chtml%2Cjavascript%2Cqml%2Cglsl&langStyle=icons&iconSize=lg&motion=pulse&contribTheme=firefly&contribRange=9m&contribMode=focus&bio=I+am+an+aspiring+systems+developer+from+Lille%2C+currently+studying+networking+%40+Université+de+Lille." width="100%" alt="Terminal identity card" />

</div>

<div align="center">

![Header](./assets/aboutme-banner.png)
---

</div>

I am a student @Université de Lille on the **DEUST Infrastructures Numeriques** studying networking as bridge towards
**Computer Science** and **Systems Development**.

I pass my day-to-day maintaining my homelab, coding for my personal projects and learning computer science & system
development by myself.<br>
I also deeply enjoy playing factory building games, simulation games and reading about Arknight's world.

My plans for the future are finishing a **Licence en informatique** and go for a **PhD in Computer Science** contributing
on the field along the way.<br>
Getting experience and contributing on the field via work is also in my to-do list!

Feel free to contact me to get to know me or for further information!
 
<div align="center">

![Header](./assets/myskills-banner.png)
---

</div>

### [ Languages ]
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)<br>
Most proficient with - Use daily for automation scripts, small app building, discord bots...

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)<br>
Intermediate level - Use it for pure performance, mostly CLI tools.

![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)<br>
Currently learning - Soon to-be daily driver for systems development and memory safety-dependent software.

![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)<br>
Occasional use - For simpler automation than python where using commands and running the script very frequently is expected

### [ Technologies ]
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)<br>
Daily work driver - Arch on my thinkpad for latest releases and customizability, Debian on my homelab for stability.

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)<br>
Homelab containers - Use it in my homelab to host multiple containers with a service each aswell as making my own images.

![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)<br>
Reverse proxy - Running multiple server blocks listening on a servername and redirecting towards an external container port.

<div align="center">

![Header](./assets/featuredprojects-banner.png)
---

</div>
 
### [[ Homelab ]](https://github.com/karch00/homelab-containers)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

Personal server running on an old Lenovo V155-15API laptop.<br>
Features a modest AMD Ryzen 5 3500U with 18GB DDR4 RAM and a 256GB NVMe for the OS and quick-access data + 
1TB HDD for persistent data and stockage. Connected via Cat5e to my home router, previously bridged to a Cisco 1800
fully configured with a subnet + NAT.

Runs Debian headless with a minimal configuration to reduce overhead consumption. SSH configured to a non-default port with
keys needed to connect. Domain name set up, each service associated to a CNAME. Ports managed via iptables. Certs set up by CertBot.<br>
Nginx serves as a reverse proxy, listening on the server name and redirecting towards the correct port depending on service.
50x errors are handled via redirection towards a plain html unavailable page.<br>
For more info on each service, visit the repo.




### [[ Babel-OS ]](https://github.com/karch00/babel-os)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

Built using the **discord.py** python library alongside **asyncpg** for async database handling.<br>
Created a custom-built asynchronous logging system for better debugging and event managing, alongisde
a system of sentinels and signals to better manage function returns. Completely modular, although development paused.<br>
Running 24/7 on my homelab, 99% uptime.

Worth mentioning PostgreSQL and SQL since I had to work with databases, but I am not confiden with the technology yet.<br>

 
### [[ Taquin ]](https://github.com/karch00/taquin)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

Simple student TUI game built using raw C in under a week.<br>
Uses ANSI codes and the termios C library to manipulate and manage the terminal states (Cursor, screen clearing, raw/canonical mode, printing, colored printing).<br>
Required a fair amount of system research to understand and apply TTY and OS notions.
