<div align="center">
<!-- Unique SVG Hero Header Banner -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%">
  <defs>
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0F172A" />
      <stop offset="50%" stop-color="#1E1B4B" />
      <stop offset="100%" stop-color="#0284C7" />
    </linearGradient>
    <linearGradient id="text-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#38BDF8" />
      <stop offset="50%" stop-color="#818CF8" />
      <stop offset="100%" stop-color="#C084FC" />
    </linearGradient>
    <linearGradient id="accent-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#F43F5E" />
      <stop offset="100%" stop-color="#FB923C" />
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
  </defs>
  <!-- Background Card -->
  <rect width="1200" height="320" rx="16" fill="url(#bg-grad)" />
  <!-- Abstract Grid & Circuit Decorative Elements -->
  <g opacity="0.12" stroke="#FFFFFF" stroke-width="1">
    <path d="M 0,40 L 1200,40 M 0,80 L 1200,80 M 0,120 L 1200,120 M 0,160 L 1200,160 M 0,200 L 1200,200 M 0,240 L 1200,240 M 0,280 L 1200,280" />
    <path d="M 100,0 L 100,320 M 200,0 L 200,320 M 300,0 L 300,320 M 400,0 L 400,320 M 500,0 L 500,320 M 600,0 L 600,320 M 700,0 L 700,320 M 800,0 L 800,320 M 900,0 L 900,320 M 1000,0 L 1000,320 M 1100,0 L 1100,320" />
  </g>
  <!-- Glowing Accent Lines -->
  <path d="M 60 40 L 1140 40" stroke="url(#text-grad)" stroke-width="3" opacity="0.6" filter="url(#glow)" />
  <path d="M 60 280 L 1140 280" stroke="url(#accent-grad)" stroke-width="2" opacity="0.5" />
  <!-- Code Decor Accent -->
  <text x="75" y="100" font-family="monospace" font-size="18" fill="#38BDF8" opacity="0.8">&lt;developer&gt;</text>
  <text x="1075" y="240" font-family="monospace" font-size="18" fill="#C084FC" opacity="0.8">&lt;/developer&gt;</text>
  <!-- Main Name Typography -->
  <text x="600" y="155" text-anchor="middle" font-family="system-ui, -apple-system, sans-serif" font-weight="900" font-size="54" fill="url(#text-grad)" filter="url(#glow)" letter-spacing="4">
    LOHITH RAJENDRAN
  </text>
  <!-- Subtitle Tagline -->
  <text x="600" y="205" text-anchor="middle" font-family="system-ui, -apple-system, sans-serif" font-weight="600" font-size="22" fill="#E2E8F0" letter-spacing="2">
    🚀 FULL-STACK SOFTWARE ENGINEER | REACT &amp; DJANGO SPECIALIST
  </text>
  <!-- Key Pills -->
  <g transform="translate(340, 230)">
    <rect x="0" y="0" width="150" height="32" rx="16" fill="#1E293B" stroke="#38BDF8" stroke-width="1.5" />
    <text x="75" y="21" text-anchor="middle" font-family="sans-serif" font-size="13" font-weight="bold" fill="#38BDF8">⚛️ React / Vite</text>
    
    <rect x="180" y="0" width="160" height="32" rx="16" fill="#1E293B" stroke="#818CF8" stroke-width="1.5" />
    <text x="260" y="21" text-anchor="middle" font-family="sans-serif" font-size="13" font-weight="bold" fill="#818CF8">🐍 Python / Django</text>
    <rect x="360" y="0" width="160" height="32" rx="16" fill="#1E293B" stroke="#C084FC" stroke-width="1.5" />
    <text x="440" y="21" text-anchor="middle" font-family="sans-serif" font-size="13" font-weight="bold" fill="#C084FC">🏦 Fintech &amp; APIs</text>
  </g>
</svg>
<br/><br/>
<!-- Dynamic Animated Typing Subtitle -->
<a href="https://github.com/LohithRajendran">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&height=45&lines=💻+Building+Modern+Full-Stack+Web+Applications;🔐+Architecting+Secure+Banking+%26+Financial+Systems;⚡+Fast+REST+APIs+with+Django+%26+React;💡+Transforming+Complex+Ideas+into+Clean+Code" alt="Typing Subtitle" />
</a>
<br/>
<!-- Real-Time Profile Badges -->
<p align="center">
  <a href="https://github.com/LohithRajendran">
    <img src="https://img.shields.io/github/followers/LohithRajendran?style=for-the-badge&logo=github&logoColor=white&color=0284C7&label=Followers" />
  </a>
  <a href="https://komarev.com/ghpvc/?username=LohithRajendran&label=Profile%20Views&color=818CF8&style=for-the-badge">
    <img src="https://komarev.com/ghpvc/?username=LohithRajendran&label=Profile%20Views&color=818CF8&style=for-the-badge" />
  </a>
  <a href="https://github.com/LohithRajendran?tab=repositories">
    <img src="https://img.shields.io/github/stars/LohithRajendran?style=for-the-badge&logo=github&logoColor=white&color=C084FC&label=Total%20Stars" />
  </a>
</p>
</div>
---
## ⚡ Terminal Overview
```typescript
/**
 * @file LohithRajendran.ts
 * @description Developer Profile Signature & Core Competencies
 */
interface DeveloperProfile {
  name: string;
  title: string;
  location: string;
  coreStack: string[];
  specializations: string[];
  currentProject: string;
}
const profile: DeveloperProfile = {
  name: "Lohith Rajendran",
  title: "Full-Stack Web Developer & Software Engineer",
  location: "India 🇮🇳",
  coreStack: ["Python", "Django DRF", "React.js", "JavaScript (ES6+)", "PostgreSQL", "Redis"],
  specializations: [
    "Secure JWT Authentication",
    "High-Concurrency Banking Systems",
    "RESTful API Engineering",
    "Responsive Modern UI/UX"
  ],
  currentProject: "Full-Stack Banking Management System 🏦"
};
console.log(`🚀 Welcome to ${profile.name}'s GitHub Profile!`);
```
---
## 🛠️ Technology Ecosystem & Arsenal
<table width="100%" border="0" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th width="25%" align="left">Category</th>
      <th width="75%" align="left">Technologies & Tools</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>💻 Frontend Core</b></td>
      <td>
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td><b>⚙️ Backend Core</b></td>
      <td>
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
        <img src="https://img.shields.io/badge/Django_REST-ff1744?style=for-the-badge&logo=django&logoColor=white" />
        <img src="https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td><b>🗄️ Database & Cache</b></td>
      <td>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td><b>🧰 Developer Tools</b></td>
      <td>
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
        <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
        <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
      </td>
    </tr>
  </tbody>
</table>
<br/>
<div align="center">
  <h3>🎨 Visual Skill Matrix</h3>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,django,postgres,redis,html,css,js,react,vite,git,github,vscode,postman&perline=7" />
  </a>
</div>
---
## 🚀 Featured Project Showcase
<div align="center">
<table width="100%" border="0" cellspacing="0" cellpadding="12">
  <tr>
    <td bgcolor="#0F172A" style="border-radius: 12px;">
      <div align="center">
        <h2>🏦 SecureBank — Full-Stack Banking Application</h2>
        <p><i>A complete enterprise-grade financial management web application built with React and Django DRF.</i></p>
      </div>
      <hr/>
      <ul>
        <li>🔐 <b>JWT Authentication & Security:</b> Token-based login, refresh rotation, and protected routes.</li>
        <li>🏦 <b>Account Management:</b> Instant digital bank account opening with welcome balance bonuses.</li>
        <li>💸 <b>Dual Transfer Engine:</b> Transfer money by Account Number or Web ID (UPI-style fast pay).</li>
        <li>📊 <b>Interactive Dashboard:</b> Real-time balance updates, transaction filtering, and audit history.</li>
        <li>⚡ <b>Performance Layer:</b> High-speed Django REST APIs backed by PostgreSQL/SQLite & Redis caching.</li>
      </ul>
      <br/>
      <div align="center">
        <a href="https://github.com/LohithRajendran/Full-stack-Banking-Management-System">
          <img src="https://img.shields.io/badge/📂_View_Full_Repository-0284C7?style=for-the-badge&logo=github&logoColor=white" />
        </a>
      </div>
    </td>
  </tr>
</table>
</div>
---
## 📊 GitHub Analytics & Insights
<div align="center">
<table border="0" width="100%">
  <tr align="center">
    <td width="50%">
      <img width="100%" src="https://github-readme-stats.vercel.app/api?username=LohithRajendran&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&title_color=38BDF8&icon_color=818CF8" />
    </td>
    <td width="50%">
      <img width="100%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LohithRajendran&layout=compact&theme=tokyonight&hide_border=true&title_color=38BDF8" />
    </td>
  </tr>
</table>
<br/>
<img width="100%" src="https://github-readme-streak-stats.herokuapp.com/?user=LohithRajendran&theme=tokyonight&hide_border=true&background=0F172A&stroke=38BDF8&alarm=F43F5E" />
</div>
---
## 📫 Connect & Reach Out
<div align="center">
<p align="center">
  <a href="https://github.com/LohithRajendran">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:lohithrajendran@example.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
<br/>
<!-- Custom Footer SVG Banner -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 100" width="100%">
  <defs>
    <linearGradient id="footer-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0F172A" />
      <stop offset="50%" stop-color="#1E1B4B" />
      <stop offset="100%" stop-color="#0F172A" />
    </linearGradient>
  </defs>
  <rect width="1200" height="100" rx="12" fill="url(#footer-grad)" />
  <text x="600" y="58" text-anchor="middle" font-family="sans-serif" font-size="16" font-weight="bold" fill="#94A3B8">
    ⚡ Designed with Passion by Lohith Rajendran • Keep Building &amp; Innovating 🚀
  </text>
</svg>
</div>
