<!-- ============================== HEADER ============================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078D4,100:00C6FF&height=210&section=header&text=Hicham%20Harmate&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=SaaS%20Architect%20%26%20Fullstack%20Engineer&descSize=20&descAlignY=60&animation=fadeIn" alt="Header" width="100%"/>

<a href="https://hichamhr.com">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=0078D4&center=true&vCenter=true&width=640&height=45&lines=POS+Systems+%C2%B7+Multi-tenant+SaaS;Real-time+IoT+%C2%B7+MQTT+%C2%B7+ESC%2FPOS;Laravel+%2B+Next.js+%C2%B7+Docker+%C2%B7+Nginx;Offline-first+%C2%B7+Resilient+by+design" alt="Typing SVG" />
</a>

<br/>

<a href="https://hichamhr.com"><img src="https://img.shields.io/badge/Portfolio-hichamhr.com-0078D4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/HichamHr"><img src="https://img.shields.io/badge/LinkedIn-HichamHr-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:harmate.hicham@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Open%20to-Collaboration-2ea44f?style=for-the-badge" alt="Open to collaboration"/>

</div>

---

## 👋 About Me

I bridge the gap between **complex cloud logic** and **real-world hardware**. I design and ship SaaS platforms that keep working when the network doesn't, and talk to printers, scanners and scales in real time.

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ What I build
- 🛒 **POS SaaS**: multi-tenant architectures with offline-first sync for retail
- 📡 **Real-time IoT**: MQTT between SaaS backends and on-site hardware
- 🕷️ **Data extraction**: distributed, resilient scraping engines with anti-bot handling
- ⚙️ **Reliability**: Docker orchestration and Nginx reverse proxies built for high uptime

</td>
<td width="50%" valign="top">

### 🎯 Principles
- 🔌 **Offline-first**: a shop never stops selling
- ⚡ **Low latency**: hardware events in milliseconds
- 🔐 **Secure by default**: tenant isolation, audited code paths
- 🧪 **Tested**: Pest (PHP) and Playwright (E2E)

</td>
</tr>
</table>

---

## 🧭 Architecture at a Glance

```mermaid
flowchart LR
    A["🖥️ POS Client<br/>Next.js · Offline-first"] <-->|REST / WebSocket| B["☁️ SaaS Core<br/>Laravel · Multi-tenant"]
    B --> C[("🐘 PostgreSQL")]
    B <--> D[("⚡ Redis<br/>Queues · Cache")]
    B <-->|MQTT| E["📡 Mosquitto Broker"]
    E <--> F["🖨️ ESC/POS Printer"]
    E <--> G["🔍 HID Scanner"]
    E <--> H["⚖️ IoT Scale"]
```

---

## 🛠️ Tech Stack

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **SaaS Core** | ![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB) |
| **Real-time & IoT** | ![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![WebSockets](https://img.shields.io/badge/-WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white) |
| **Data & Infra** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| **Performance** | ![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Gunicorn](https://img.shields.io/badge/-Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white) |
| **Testing** | ![Pest](https://img.shields.io/badge/-Pest-F28D1A?style=flat-square&logo=php&logoColor=white) ![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |

</div>

---

## 📡 IoT & SaaS Standards

<details>
<summary><b>🔌 Real-time protocol</b></summary>
<br/>

**MQTT (Mosquitto)** for real-time peripheral state management between the SaaS backend and on-site devices.

</details>

<details>
<summary><b>🖨️ Hardware integration</b></summary>
<br/>

- ESC/POS thermal printing
- HID barcode scanners
- IoT weighing scales

</details>

<details>
<summary><b>🧪 Quality & testing</b></summary>
<br/>

- Unit and integration tests with **Pest** (PHP)
- End-to-end tests with **Playwright**
- CI with **GitHub Actions**

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=HichamHr&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&rank_icon=github" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HichamHr&layout=compact&theme=tokyonight&hide=html,css&hide_border=true" alt="Top languages"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=HichamHr&theme=tokyonight&hide_border=true" alt="Streak" width="85%"/>

</div>

---

## 🤝 Let's Connect

<div align="center">

Have a POS, SaaS or IoT project in mind? Let's talk.

<a href="https://hichamhr.com"><img src="https://img.shields.io/badge/🌐%20Visit%20Portfolio-0078D4?style=for-the-badge" alt="Portfolio"/></a>
<a href="mailto:harmate.hicham@gmail.com"><img src="https://img.shields.io/badge/📧%20Send%20an%20Email-EA4335?style=for-the-badge" alt="Email"/></a>
<a href="https://linkedin.com/in/HichamHr"><img src="https://img.shields.io/badge/💼%20Connect%20on%20LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=HichamHr&color=0078D4&style=flat-square&label=PROFILE+VIEWS" alt="Profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078D4,100:00C6FF&height=110&section=footer" alt="Footer" width="100%"/>

</div>
