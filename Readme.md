<div align="center">

  <!-- ========== STYLES ========== -->
  <style>
    /* base reset & dark bg */
    body { background: #0D1117; }

    /* all images, links, blocks get smooth transitions */
    * {
      transition: all 0.25s ease-in-out;
    }

    /* ---- floating logo animation ---- */
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-12px); }
      100% { transform: translateY(0px); }
    }
    .float-logo {
      display: inline-block;
      animation: float 3.5s ease-in-out infinite;
    }
    .float-logo:hover {
      animation-duration: 0.8s;
      filter: drop-shadow(0 0 18px #0A84FF);
    }

    /* ---- glowing header fade-in ---- */
    @keyframes glowPulse {
      0% { opacity: 0.9; filter: brightness(1); }
      50% { opacity: 1; filter: brightness(1.25) drop-shadow(0 0 30px #0A84FF); }
      100% { opacity: 0.9; filter: brightness(1); }
    }
    .glow-header img {
      animation: glowPulse 4s ease-in-out infinite;
      border-radius: 18px;
    }

    /* ---- badge hover effects ---- */
    .badge-link {
      display: inline-block;
      transform: scale(1);
    }
    .badge-link:hover {
      transform: scale(1.08) translateY(-3px);
      filter: drop-shadow(0 0 20px rgba(10, 132, 255, 0.7));
    }
    .badge-link img {
      transition: 0.2s;
    }

    /* ---- tech icons hover ---- */
    .tech-icon {
      display: inline-block;
      transition: 0.3s;
      margin: 4px;
    }
    .tech-icon:hover {
      transform: scale(1.18) rotate(-3deg);
      filter: drop-shadow(0 0 18px #34C759);
    }

    /* ---- project table row hover (glow border) ---- */
    .project-table tr {
      transition: 0.3s;
      border-radius: 16px;
    }
    .project-table tr:hover {
      background: rgba(10, 132, 255, 0.06);
      box-shadow: 0 0 0 2px #0A84FF, 0 0 30px rgba(10, 132, 255, 0.2);
      transform: scale(1.005);
    }
    .project-table td, .project-table th {
      padding: 12px 10px;
      vertical-align: middle;
      border-bottom: 1px solid rgba(255,255,255,0.04);
    }

    /* ---- stat cards glow border ---- */
    .stat-card {
      transition: 0.3s;
      border-radius: 18px;
      overflow: hidden;
    }
    .stat-card:hover {
      transform: scale(1.02);
      box-shadow: 0 0 40px rgba(10, 132, 255, 0.25);
    }
    .stat-card img {
      border-radius: 18px;
    }

    /* ---- footer link hover ---- */
    .footer-link {
      text-decoration: none;
      font-weight: 500;
      transition: 0.2s;
    }
    .footer-link:hover {
      color: #34C759 !important;
      text-shadow: 0 0 18px #34C759;
    }

    /* ---- misc ---- */
    .section-title {
      background: linear-gradient(90deg, #0A84FF, #BF5AF2);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: 700;
    }
  </style>

  <!-- ========== HEADER ========== -->
  <div class="glow-header">
    <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,30:0A84FF,70:34C759,100:BF5AF2&height=160&section=header&text=Isara%20Dilnuka&fontSize=42&fontColor=ffffff&animation=fadeIn" width="100%" alt="Header" />
  </div>

  <!-- ========== LOGO (FLOATING) ========== -->
  <a href="https://dilnuka13.github.io/my/">
    <img class="float-logo" src="https://dilnuka13.github.io/my/titlebar.png" width="85" height="85" alt="Isara Dilnuka Logo" style="border-radius: 22px; margin-top: -30px; border: 2px solid rgba(255,255,255,0.06);" />
  </a>

  <br/><br/>

  <!-- ========== TYPING SVG ========== -->
  <a href="https://dilnuka13.github.io/my/">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=30D158&center=true&vCenter=true&width=600&lines=Full-Stack+Web+Developer+%F0%9F%92%BB;UI%2FUX+%26+Graphic+Designer+%F0%9F%8E%A8;Creative+Technologist+%F0%9F%9A%80;Freelance+Creator+Since+2018+%E2%9A%A1" alt="Typing SVG" />
  </a>

  <p>
    <b>Crafting modern web apps, high-performance systems & fluid digital experiences.</b><br/>
    <i>Based in Sri Lanka 🇱🇰 • 50+ Completed Projects</i>
  </p>

  <!-- ========== BADGES (HOVER SCALE + GLOW) ========== -->
  <p>
    <a class="badge-link" href="https://dilnuka13.github.io/my/"><img src="https://img.shields.io/badge/Portfolio-Live_Site-34C759?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
    <a class="badge-link" href="https://github.com/dilnuka13"><img src="https://img.shields.io/badge/Code_Hub-@dilnuka13-0A84FF?style=for-the-badge&logo=github&logoColor=white" alt="Active Projects Hub" /></a>
    <a class="badge-link" href="mailto:in.fo.dilnuka@outlook.com"><img src="https://img.shields.io/badge/Email-Outlook-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
    <a class="badge-link" href="https://www.linkedin.com/in/isara-dilnuka-ab8161352/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a class="badge-link" href="https://x.com/Dilnuka13x"><img src="https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  </p>

</div>

---

### 🌐 GitHub Ecosystem & Workspace

> 🚀 **Primary Engineering Hub:** **[@dilnuka13](https://github.com/dilnuka13)** — *All active repositories, production builds, web applications & open‑source codebases reside here.*
> 
> 🎨 **Portfolio & Design Lab:** **[@dilnuka13x](https://github.com/dilnuka13x)** — *Personal branding, design experiments & profile showcase.*

---

### 🛠️ Tech Stack & Toolkit

<div align="center">

  <p><b>💻 Frontend & Core</b></p>
  <p>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=html" alt="HTML" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=css" alt="CSS" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=js" alt="JS" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=react" alt="React" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=tailwind" alt="Tailwind" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=bootstrap" alt="Bootstrap" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=vite" alt="Vite" /></span>
  </p>
  
  <br/>

  <p><b>⚙️ Backend, Databases & Cloud</b></p>
  <p>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=php" alt="PHP" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=firebase" alt="Firebase" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=supabase" alt="Supabase" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" /></span>
  </p>

  <br/>

  <p><b>🎨 UI/UX & Creative Tools</b></p>
  <p>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=figma" alt="Figma" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=ps" alt="Photoshop" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=pr" alt="Premiere" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=ai" alt="Illustrator" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=git" alt="Git" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=github" alt="GitHub" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=vscode" alt="VS Code" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=postman" alt="Postman" /></span>
    <span class="tech-icon"><img src="https://skillicons.dev/icons?i=vercel" alt="Vercel" /></span>
  </p>

</div>

---

### 🚀 Featured Live Projects & Systems

<div align="center">

<table class="project-table" style="width:100%; border-collapse:collapse; max-width:900px; margin:auto;">
  <thead>
    <tr style="border-bottom:2px solid #0A84FF;">
      <th style="padding:10px;">Project</th>
      <th style="padding:10px;">Type</th>
      <th style="padding:10px;">Description</th>
      <th style="padding:10px;">Live Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding:10px;"><img src="https://dmyc.space/assets/images/logo_1.png" width="34" height="34" align="center" /> <b>DMY&SC</b></td>
      <td style="padding:10px;"><code>Web Application</code></td>
      <td style="padding:10px;">Modern digital portal & community web presence</td>
      <td style="padding:10px;"><a href="https://dmyc.space/" style="color:#0A84FF;font-weight:600;">🔗 Live Demo</a></td>
    </tr>
    <tr>
      <td style="padding:10px;"><img src="https://dilnuka13.github.io/DE-NOVA-READER/logo.png" width="34" height="34" align="center" /> <b>DE Education</b></td>
      <td style="padding:10px;"><code>EdTech Platform</code></td>
      <td style="padding:10px;">A/L Past Papers, Schemes, AI Agents & Results</td>
      <td style="padding:10px;"><a href="https://dilnuka13.github.io/AL/" style="color:#0A84FF;font-weight:600;">🌐 Web App</a> • <a href="https://hppojrbfhzttzvlvovre.supabase.co/storage/v1/object/public/app-files/DE%20E%201.0v.apk" style="color:#34C759;font-weight:600;">📱 APK</a></td>
    </tr>
    <tr>
      <td style="padding:10px;"><img src="https://dilnuka13.github.io/DE-NOVA-READER/logo.png" width="34" height="34" align="center" /> <b>DE NOVA Reader</b></td>
      <td style="padding:10px;"><code>Productivity App</code></td>
      <td style="padding:10px;">Minimalist, high‑performance browser PDF reader</td>
      <td style="padding:10px;"><a href="https://dilnuka13.github.io/DE-NOVA-READER/" style="color:#0A84FF;font-weight:600;">🔗 Launch App</a></td>
    </tr>
    <tr>
      <td style="padding:10px;"><img src="https://mp-ims.web.app/logo.png" width="34" height="34" align="center" /> <b>MP IMS</b></td>
      <td style="padding:10px;"><code>Management System</code></td>
      <td style="padding:10px;">Full‑featured institutional management portal</td>
      <td style="padding:10px;"><a href="https://mp-ims.web.app/" style="color:#0A84FF;font-weight:600;">🔗 Live Demo</a></td>
    </tr>
  </tbody>
</table>

</div>

<div align="right">
  <a href="https://github.com/dilnuka13?tab=repositories"><b>Explore all 50+ repositories on @dilnuka13 →</b></a>
</div>

---

### 📊 GitHub Activity & Analytics

<div align="center">

  <!-- STAT CARDS WITH HOVER GLOW BORDER -->
  <a class="stat-card" href="https://github.com/dilnuka13">
    <img src="https://github-readme-stats.vercel.app/api?username=dilnuka13&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=30D158&icon_color=0A84FF&text_color=EBEBF5" alt="GitHub Stats" width="48%" />
  </a>
  <a class="stat-card" href="https://github.com/dilnuka13">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dilnuka13&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=30D158&text_color=EBEBF5" alt="Top Languages" width="48%" />
  </a>
  <br/><br/>
  <a class="stat-card" href="https://github.com/dilnuka13">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=dilnuka13&theme=tokyonight&hide_border=true&background=0D1117&ring=34C759&fire=FF9F0A&currStreakLabel=30D158" alt="GitHub Streak" width="97%" />
  </a>

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:BF5AF2,50:0A84FF,100:34C759&height=100&section=footer" width="100%"/>
  <p>
    <b>Built with passion by Isara Dilnuka</b> • 
    <a class="footer-link" href="https://dilnuka13.github.io/my/" style="color:#EBEBF5;">Website</a> • 
    <a class="footer-link" href="https://github.com/dilnuka13" style="color:#EBEBF5;">@dilnuka13</a> • 
    <a class="footer-link" href="https://github.com/dilnuka13x" style="color:#EBEBF5;">@dilnuka13x</a>
  </p>
</div>
