<!-- README: Omar Issa - Dark Neon Profile -->
<!-- Soft glowing particles (single neon color #00FFF0) with static neon-glow headings -->
<!-- Copy this file to README.md -->

<!-- Header + animated SVG background -->
<div align="center" style="position:relative;overflow:hidden;padding:28px;border-radius:12px;background:#07070a;">

  <!-- Animated soft glowing particles (SVG) -->
  <!-- Single neon color: #00FFF0 -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="none" style="position:absolute;left:0;top:0;mix-blend-mode:screen;pointer-events:none;opacity:0.85;">
    <defs>
      <filter id="blur">
        <feGaussianBlur stdDeviation="8" result="blur"/>
        <feColorMatrix in="blur" type="matrix"
          values="0 0 0 0 0
                  0 0 0 0 1
                  0 0 0 0 1
                  0 0 0 0.6 0" result="col"/>
        <feBlend in="SourceGraphic" in2="col" mode="screen"/>
      </filter>
    </defs>

    <!-- group of soft particles (positions randomized visually) -->
    <g filter="url(#blur)">
      <circle cx="120" cy="40" r="18" fill="#00FFF0" opacity="0.14">
        <animate attributeName="cx" dur="18s" values="120;110;140;120" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="16s" values="40;60;30;40" repeatCount="indefinite"/>
        <animate attributeName="opacity" dur="8s" values="0.12;0.22;0.12" repeatCount="indefinite"/>
      </circle>

      <circle cx="300" cy="70" r="26" fill="#00FFF0" opacity="0.11">
        <animate attributeName="cx" dur="22s" values="300;320;280;300" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="20s" values="70;90;50;70" repeatCount="indefinite"/>
        <animate attributeName="opacity" dur="10s" values="0.08;0.18;0.08" repeatCount="indefinite"/>
      </circle>

      <circle cx="520" cy="28" r="14" fill="#00FFF0" opacity="0.13">
        <animate attributeName="cx" dur="20s" values="520;540;500;520" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="14s" values="28;48;18;28" repeatCount="indefinite"/>
        <animate attributeName="opacity" dur="7s" values="0.1;0.2;0.1" repeatCount="indefinite"/>
      </circle>

      <circle cx="760" cy="120" r="30" fill="#00FFF0" opacity="0.10">
        <animate attributeName="cx" dur="24s" values="760;740;780;760" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="18s" values="120;140;100;120" repeatCount="indefinite"/>
        <animate attributeName="opacity" dur="11s" values="0.07;0.17;0.07" repeatCount="indefinite"/>
      </circle>

      <circle cx="980" cy="48" r="20" fill="#00FFF0" opacity="0.12">
        <animate attributeName="cx" dur="19s" values="980;960;1000;980" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="15s" values="48;68;28;48" repeatCount="indefinite"/>
        <animate attributeName="opacity" dur="9s" values="0.09;0.19;0.09" repeatCount="indefinite"/>
      </circle>

      <!-- a few subtle small particles -->
      <circle cx="200" cy="160" r="8" fill="#00FFF0" opacity="0.07">
        <animate attributeName="cx" dur="16s" values="200;210;190;200" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="21s" values="160;170;150;160" repeatCount="indefinite"/>
      </circle>
      <circle cx="440" cy="150" r="6" fill="#00FFF0" opacity="0.06">
        <animate attributeName="cx" dur="18s" values="440;460;420;440" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="14s" values="150;160;140;150" repeatCount="indefinite"/>
      </circle>
      <circle cx="1120" cy="180" r="10" fill="#00FFF0" opacity="0.05">
        <animate attributeName="cx" dur="26s" values="1120;1100;1140;1120" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="20s" values="180;190;170;180" repeatCount="indefinite"/>
      </circle>
    </g>
  </svg>

  <!-- Main centered content -->
  <div style="position:relative; z-index:2; color:#e6f7f7; padding:18px; max-width:920px; margin:0 auto;">

    <!-- Typing header (image) -->
    <h1 style="margin:6px 0 6px 0;">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00FFF0&center=true&vCenter=true&width=680&lines=Hey+there!+I'm+Omar+Issa+👋;Back-End+Developer+⚙️;Node.js+%7C+Express.js+%7C+APIs" alt="Typing SVG" />
    </h1>

    <!-- Subheading with glow -->
    <p style="margin:6px 0 0 0;color:#bfeff0;font-size:16px;text-shadow:0 0 10px rgba(0,255,240,0.12);">
      Building secure, scalable, and maintainable backend systems for real products. Focused on APIs, auth, and performance.
    </p>

  </div>
</div>

<br />

<!-- MAIN CONTENT -->
<!-- Glow headings use inline styles (static glow) -->
<h2 style="color:#00FFF0; text-shadow:0 0 12px #00FFF0; margin-top:6px;">🧠 About Me</h2>

**Dedicated** and **self-taught** Back-End Developer with strong experience in **Node.js**, **Express.js**, and database
management using **MongoDB**, **PostgreSQL**, and **MySQL**. Experienced in building **scalable RESTful APIs**,
**authentication systems**, and **full-stack applications** using **React**, **TypeScript**, and modern JavaScript.
Passionate about developing **efficient**, **secure**, and **maintainable** backend systems. Currently working as a
backend developer on **SoliMaking**, a short film platform **(in progress)**.

---

<h2 style="color:#00FFF0; text-shadow:0 0 12px #00FFF0;">⚙️ Tech Stack</h2>

#### 💻 **Languages & Frameworks**
![Node.js](https://img.shields.io/badge/Node.js-0B5D1E?style=for-the-badge&logo=node.js&logoColor=00FF88)
![Express.js](https://img.shields.io/badge/Express.js-111111?style=for-the-badge&logo=express&logoColor=00FFF0)
![JavaScript](https://img.shields.io/badge/JavaScript-0E0E0E?style=for-the-badge&logo=javascript&logoColor=FFD600)
![TypeScript](https://img.shields.io/badge/TypeScript-1B1F23?style=for-the-badge&logo=typescript&logoColor=00AFFF)
![Python](https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=FFE873)
![React](https://img.shields.io/badge/React-0E0E0E?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-1B1F23?style=for-the-badge&logo=html5&logoColor=FF4500)
![CSS3](https://img.shields.io/badge/CSS3-0B0B0B?style=for-the-badge&logo=css3&logoColor=00BFFF)

#### 🧰 **Databases**
![MongoDB](https://img.shields.io/badge/MongoDB-001A00?style=for-the-badge&logo=mongodb&logoColor=00FF88)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-101820?style=for-the-badge&logo=postgresql&logoColor=00BFFF)
![MySQL](https://img.shields.io/badge/MySQL-0E0E0E?style=for-the-badge&logo=mysql&logoColor=00FFFF)

#### 🛠️ **Tools & Environment**
![Git](https://img.shields.io/badge/Git-191919?style=for-the-badge&logo=git&logoColor=F05033)
![GitHub](https://img.shields.io/badge/GitHub-0E0E0E?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0B1E2C?style=for-the-badge&logo=docker&logoColor=00AFFF)
![Postman](https://img.shields.io/badge/Postman-1A0E00?style=for-the-badge&logo=postman&logoColor=FF6C37)
![VS Code](https://img.shields.io/badge/VS%20Code-0E0E0E?style=for-the-badge&logo=visualstudiocode&logoColor=00BFFF)

#### 🔒 **Security**
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=00FFF0)
![Bcrypt](https://img.shields.io/badge/Bcrypt-111111?style=for-the-badge&logo=lock&logoColor=00FF88)
![Middleware](https://img.shields.io/badge/Middleware-111111?style=for-the-badge&logo=shield&logoColor=00BFFF)
![Env](https://img.shields.io/badge/.ENV-111111?style=for-the-badge&logo=dotenv&logoColor=00FF88)

---

<h2 style="color:#00FFF0; text-shadow:0 0 12px #00FFF0;">🧩 Featured Projects</h2>

#### 🧱 **Task Manager API**
RESTful API with **Node.js**, **Express.js**, and **MongoDB**, featuring full **CRUD** and **JWT authentication**.

#### 🛒 **Store API**
A **scalable** and **high-performance** API with **filtering**, **pagination**, and **clean architecture** principles.

#### 🔐 **JWT Login/Register App**
Secure **authentication & authorization** system using **JWT**, **bcrypt**, and Express **middleware**.

#### 💼 **Jobs Tracker (Full Stack)**
Full-stack job management app featuring **JWT authentication**, **job analytics**, and CRUD operations.  
Built with **React (frontend)** and **Node.js/Express.js (backend)**.  
**[🔗 Live Demo](https://jobs-frontend-one.vercel.app/)**

#### 🎬 **SoliMaking (Backend – In Progress)**
Backend for a short film platform integrating **Vimeo API** for uploads, thumbnails, and metadata management.

---

<h2 style="color:#00FFF0; text-shadow:0 0 12px #00FFF0;">📊 GitHub Stats</h2>

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Omar-Issa1&show_icons=true&theme=react&hide_border=true&bg_color=0D1117&title_color=00FFF0&icon_color=00FFF0" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=Omar-Issa1&theme=react&hide_border=true&background=0D1117&ring=00FFF0&fire=00FFF0" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Omar-Issa1&theme=react-dark&hide_border=true&color=00FFF0&line=00FFF0&point=00FFF0" />
</p>

---

<h2 style="color:#00FFF0; text-shadow:0 0 12px #00FFF0;">📫 Connect With Me</h2>

<p align="center">
  <a href="mailto:omar.issa.contact@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-0D1117?style=for-the-badge&logo=gmail&logoColor=FF4B4B" />
  </a>
  <a href="https://github.com/Omar-Issa1">
    <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  </a>
  <a href="https://www.linkedin.com/in/omar-issa-788987384/">
    <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00AFFF" />
  </a>
</p>

---

<h3 align="center" style="color:#00FFF0; text-shadow:0 0 12px #00FFF0;">
✨ “Suffering does not mean that you will succeed. You can suffer and die.” ✨
</h3>
