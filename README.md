<h1 align="center">Hai, I'm Maya Holzer 👋🌸</h1>
<p align="center">
  <em>20 years old 🌸 | Application Developer Apprentice @ <a href="https://www.knapp.com/">KNAPP AG</a> <img src="Knapp_Logo.svg" alt="KNAPP Logo" width="20"/> | Based in Graz, Austria 🇦🇹</em>
</p>

<div align="center">
  <br>
<a href="https://www.common-ground.homes" target="_blank" align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Try%20CommonGround%20now!%20%E2%9C%A8%F0%9F%92%96%20%3A)-ya?style=for-the-badge&logo=rocket&logoColor=%23673ab7&logoSize=auto&labelColor=%23f4b2dd&color=%23F5BAE0">
  <br>
  <br>
</a>

</div>
<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2500&pause=500&color=FF79C6&center=true&vCenter=true&width=900&lines=Code+with+Purpose%2C+Life+with+Intention+%F0%9F%92%BB%F0%9F%8C%BF;+Full-Stack+Dev+on+a+mission+to+build+useful%2C+elegant+things+;+Passionate+about+autonomy%2C+self-hosting%2C+and+lifelong+learning;+Tech-savvy%2C+people-conscious%2C+and+always+up+for+a+challenge;+Blending+logic%2C+empathy%2C+and+vision%E2%80%94one+project+at+a+time" alt="Typing SVG" /></a>
</p>

---

<h2 align="center">🛠️ Tech Stack</h2>

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,qt,js,ts,html,css,angular,supabase,java,kotlin,flutter,c,cpp,php,discordjs&perline=20" alt="Tech Stack" />
  <img src="https://skillicons.dev/icons?i=unreal,docker,kubernetes,git,linux,mysql,postgresql,figma,pr,ps,ae,&perline=20" alt="Tech Stack" />
</div>

---

<h2 align="center">🚀 Projects I'm Proud Of</h2>

### 🏠 [Common Ground](common-ground.homes) - Flat Management App    `2025` `🚧 WIP 🚧`
Comprehensive mobile-first app that makes shared living actually enjoyable! Features collaborative shopping lists, expense tracking with automated debt calculations, real-time presence tracking, and receipt uploads.
> Angular 19 • Ionic 7 • Capacitor • Supabase • TypeScript • PostgreSQL

### 🤖 [AustriaSkills Robot WebInterface](https://github.com/H0lz3r-x64/AustriaSkills-Robot-WebInterface)    `2023`
Responsive web interface for monitoring and controlling competition robots, with real-time metrics and interactive path visualization. Built for both desktop and mobile browsers.
<br>My first real working web application.
> JavaScript • HTML/CSS • Canvas API • Real-time data

### 📊 [DB-Table-Export](https://github.com/H0lz3r-x64/DB-Table-Export) - Report Generation    `2023`
Customizable report generation for managing educational courses and apprentice data, creating self-contained HTML and PDF exports.
> Python • HTML • PDF generation

### 🔄 ProjectMigrater - Enterprise Migration System    `2025`
*(Department internal)* Comprehensive migration system for autonomous shuttle data, using versioned scripts to transform JSON/Protobuf between protocol versions. Focus on clean software design.
> Python • Flask • Angular • JSON • REST API

```mermaid
sequenceDiagram
    participant User
    participant Interface as CLI/API Interface
    participant Manager as Migration Manager
    participant Discovery as Class Discovery
    participant Scripts as Migration Scripts
    participant Data as Project Data
    
    User->>Interface: Upload project file + config
    Interface->>Manager: Initialize with file & feedback service
    Manager->>Manager: Load configuration & global params
    Manager->>Data: Load and parse project JSON
    Manager->>Data: Extract current protocol version
    
    User->>Interface: Request setup
    Interface->>Manager: setup()
    Manager->>Discovery: Retrieve available scripts
    Discovery->>Scripts: Load migration & utility classes
    Manager-->>Interface: Return current version & global params
    
    User->>Interface: Request migration with target version
    Interface->>Manager: run(RunConfig)
    Manager->>Discovery: Filter scripts by version range
    Discovery-->>Manager: Return applicable script classes
    Manager->>Scripts: Instantiate with parameters
    Manager->>Scripts: Validate parameters
    
    loop For each migration script (version order)
        Manager->>Scripts: Check if should apply
        Scripts->>Data: Analyze current state
        Manager->>Scripts: Execute migrate()
        Scripts->>Data: Transform data
        Scripts->>Data: Update protocol version
        Manager->>Interface: Provide feedback
    end
    
    loop For each utility script
        Manager->>Scripts: Execute migrate()
        Scripts->>Data: Apply utility transformation
        Manager->>Interface: Provide feedback
    end
    
    Manager->>Manager: Generate migration report
    Manager-->>Interface: Return result with migrated data
    Interface-->>User: Provide output file & report

```
---

<h2 align="center">✨ Current Focus: Common Ground</h2>

<p align="center">A web-based app with mobile capabilities designed to simplify shared living arrangements. It centralizes all aspects of communal living, from scheduling and finances to shopping and tasks, making it easier for residents to stay organized and harmonious.</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/6014670a-6207-4033-a3da-7bafdac54aca" height="350px"/>
<img src="https://github.com/user-attachments/assets/3b40d252-d6e8-49e8-b10c-46b8a46d90de" height="350px"/>
<img src="https://github.com/user-attachments/assets/e2e46a7d-36d5-40d9-a541-3ca7ab89542a" height="350px"/>
</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/0c1173c5-1122-4dde-9c29-8e6221933786" height="350px"/>
<img src="https://github.com/user-attachments/assets/0b378665-457b-45cd-aeb3-6ec390e3dfef" height="350px"/>
<img src="https://github.com/user-attachments/assets/09fa4b7f-ac2f-4e05-8ad7-4f7abd18ec76" height="350px"/>
</p>

---

<h2 align="center">📈 GitHub Stats</h2>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=H0lz3r-x64&theme=radical&hide_border=true" alt="GitHub Streak Stats" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api?username=H0lz3r-x64&show_icons=true&theme=radical&count_private=true&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=H0lz3r-x64&langs_count=8&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
<!--   <img src="https://github-readme-activity-graph.vercel.app/graph?username=H0lz3r-x64&bg_color=0d1117&color=ff6ec7&line=ff6ec7&point=ffffff&hide_border=true" alt="GitHub Activity Graph" /> -->
</div>

<h2 align="center">💭 About Me</h2>

- 🌱 Learning while trying to enjoy these formative years
- 🏠 Working on apps that actually help people in their daily lives
- 🧠 Interested in creating tech that makes life better, not profits!
- 🎨 Blend coding with creativity to solve real problems
- 🌍 Based in Graz but connected globally
- 🔮 Dream of building technology that encourages community and cooperation

---

<h2 align="center">📫 Let’s Connect!</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/h0lz3r-x64/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
   <a href="mailto:maya.dev@posteo.net"><img src="https://img.shields.io/badge/E--Mail-%23fe99b7?&style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dracula&quote=The+true+revolutionary+is+guided+by+great+feelings+of+love&author=Ernesto+%22Che%22+Guevara&border=true" alt="Inspirational Quote" width="600px"/>
</p>
<p align="center">
  Built with 💖 by <strong>Maya Holzer</strong>.
</p>
