<div align="center"> 

![Header](./assets/header-banner.png) 

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=32&duration=3500&pause=1000&color=FAFAFA&center=true&vCenter=true&width=980&lines=Aspiring+systems+developer;Daring+CS+student;Proud+homelab+maintainer;Avid+Arknights+fan" alt="Typing SVG" /></a>

<img src="https://terminal-identity-opal.vercel.app/api?name=Pablo+Andre&username=karch00&role=CS+%26+Systems+student&tagline=Learning+by+building&command=cargo+run+github-profile&theme=obsidian%2Fgraphite&avatar=KH&pattern=pulse&width=980&height=auto&accent=%23e0bc0e&showLangs=on&showContribs=on&stats=repos%2Cfollowers&excludeLangs=css%2Clua%2Chtml%2Cjavascript%2Cqml%2Cglsl&langStyle=icons&iconSize=lg&motion=pulse&contribTheme=firefly&contribRange=9m&contribMode=focus" width="100%" alt="Terminal identity card" />

[<img src="./assets/linkedin.png" height="26" align="absmiddle" />](https://www.linkedin.com/in/pablo-andre-7b1138373)
[<img src="./assets/email.png" height="26" align="absmiddle" />](mailto:pablo.andre-benito.etu@univ-lille.fr)
<img src="./assets/discord.png" height="26" align="absmiddle" />
[<img src="./assets/arknights.png" height="26" align="absmiddle" />](https://www.krooster.com/u/khloi)

</div>




<img src="./assets/aboutme-banner.png" align="center" alt="About Me">

---

I am a student @Université de Lille on the **DEUST Infrastructures Numeriques** studying networking as bridge towards
**Computer Science** and **Systems Development**.<br>
My academic plans for the future involve starting and completing a **Bachelors in CS** 
and finishing off by going for a **PhD in Computer Science**, contributing on the field along the way.

I love passing my day-to-day maintaining my personal homelab: looking for new services, optimizing the existing ones..., 
coding personal projects such as discord bots or little scripts, and learning computer science & system development by myself 
in complete autonomy by completing roadmaps, applying what I learn and completing leetcode problems.

I am also deeply involved in playing factory building games, simulation games and specially playing and reading about Arknights'
world. I am a fan of the game(s) and find the story behind it a great parallel to the history of our world with a touch of fantasy and
sci-fi.

Feel free to contact me to get to know me or for further information!
 


<img src="./assets/myskills-banner.png" align="center" alt="My Skills">

---

<img src="./assets/languages.png" height=32 alt="Languages"><br>
**Languages I am most comfortable working with. Projects made mostly with these.**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=red)
![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

<img src="./assets/devtools.png" height=32 alt="Dev Tools"><br>
**Development tools I use daily and involve in most of my projects.**

![Zed](https://img.shields.io/badge/zedindustries-084CCF.svg?style=for-the-badge&logo=zedindustries&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

<img src="./assets/infrastructure.png" height=32 alt="Infrastructure"><br>
**Infrastructure technologies I regularly use and maintain.**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

<img src="./assets/environment.png" height=32 alt="Environments"><br>
**Development environments I use depending on the goal.**

![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)
![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)



<img src="./assets/featuredprojects-banner.png" align="center" alt="Featured Projects">

---
 
### [[ Homelab ]](https://github.com/karch00/homelab-containers)
![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)
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
Created a custom-built asynchronous logging system for better debugging and event managing, alongside
a system of sentinels and signals to better manage function returns. Completely modular, development planned to be retaken.<br>
Running 24/7 on my homelab, 99% uptime.

Worth mentioning PostgreSQL and SQL since I had to work with databases, but I am not confident with the technology yet.<br>
 
### [[ Taquin ]](https://github.com/karch00/taquin)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

Simple student TUI game built using raw C in under a week.<br>
Uses ANSI codes and the termios C library to manipulate and manage the terminal states (Cursor, screen clearing, raw/canonical mode, printing, colored printing).<br>
Required a fair amount of system research to understand and apply TTY and OS notions.
