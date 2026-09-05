<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=220&section=header&text=Jerome%20Dwight%20Bautista&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=BSIT%20Student%20and%20Aspiring%20Software%20Developer&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/jeromedwight">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=900&lines=4th+Year+BSIT+Student+at+Saint+Mary's+University;Web+and+Software+Developer;React+%2B+Node.js+%2B+MySQL+%2F+MongoDB;Building+capstone+KwartoKeeper;Always+learning+by+building" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=jeromedwight&label=Profile%20Views&color=38BDF8&style=flat" />

</div>

---

## 👋 About Me

- 🎓 4th-year **BS Information Technology** student at **Saint Mary's University**, Bayombong, Nueva Vizcaya, PH — expected graduation **2027**
- 💻 Focused on **web development**, **software development**, and **database systems**
- 🧩 Comfortable across the stack: front-end UI, back-end APIs, and relational/NoSQL databases
- 🏗️ Currently building my capstone project, **KwartoKeeper**, a dormitory management platform
- 🌱 Always improving code quality, database design, and dev workflow (Git/GitHub)
- 📍 Based in the Philippines

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,100:1a1a2e&height=3&width=100%&animation=twinkling" width="100%"/>
</div>

## 🧰 Tech Stack

**Languages & Web**

<img src="https://skillicons.dev/icons?i=html,css,js,vbnet&theme=dark" />

**Frontend / Frameworks**

<img src="https://skillicons.dev/icons?i=react,vite,tailwind,materialui&theme=dark" />

**Backend & Runtime**

<img src="https://skillicons.dev/icons?i=nodejs,express,php&theme=dark" />

**Databases**

<img src="https://skillicons.dev/icons?i=mysql,mongodb,firebase&theme=dark" />

**Mobile**

<img src="https://skillicons.dev/icons?i=kotlin,androidstudio&theme=dark" />

**Tools**

<img src="https://skillicons.dev/icons?i=vscode,visualstudio,git,github,postman,figma&theme=dark" />

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,100:1a1a2e&height=3&width=100%&animation=twinkling" width="100%"/>
</div>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏠 KwartoKeeper *(Capstone)*
Mobile-responsive dormitory/apartment occupancy monitoring and tenant information management system, built with a group at SMU for three real dormitory operators in Bayombong.

**Stack:** React · Vite · Node.js · Firebase · QRPh/InstaPay payments
**Highlights:** ISO/IEC 25010:2015 evaluation, RAD methodology, real tenant requirements docs

</td>
<td width="50%" valign="top">

### 💧 AquaTrack
Solo-built web order & inventory management system for a water refilling station — full lifecycle from schema design to deployment.

**Stack:** React (Vite) · Node.js/Express · MySQL
**Deployed:** Railway (backend) · Vercel (frontend)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☕ Felisa's Grind and Brew
Dark-themed coffee shop web application, with focus on UI components, admin dashboard styling, and a documented style guide.

**Stack:** React · Express

</td>
<td width="50%" valign="top">

### 💰 PayrollPH
Payroll management system with 2nd-cutoff deduction logic, redesigned with a dark navy fintech-inspired UI.

**Stack:** PHP · MySQL · XAMPP

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🍽️ Restaurant Reservation System
Desktop reservation system managing customer info, table availability, reservations, user roles, and reports.

**Stack:** VB.NET · Windows Forms · MySQL

</td>
<td width="50%" valign="top">

### 🎨 Café Cozy
Front-end practice project focused on page building, styling, and basic JS interactivity.

**Stack:** HTML · CSS · JavaScript

</td>
</tr>
</table>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,100:1a1a2e&height=3&width=100%&animation=twinkling" width="100%"/>
</div>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jeromedwight&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jeromedwight&layout=compact&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=jeromedwight&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=jeromedwight&theme=react-dark&hide_border=true&area=true" width="100%"/>

</div>

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/jeromedwight/jeromedwight/output/github-contribution-grid-snake.svg" width="100%"/>
</div>

<details>
<summary>⚙️ Paano i-activate 'to (one-time setup, 5 minutes lang)</summary>

1. Sa GitHub, gumawa ng bagong **special repo** na eksaktong pareho ng username mo: `jeromedwight/jeromedwight` (kung wala ka pa nito) — Public, walang README kailangan.
2. Sa loob ng repo na 'yan, gumawa ng file na `.github/workflows/snake.yml` na may lamang:

```yaml
name: generate animated snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch: {}
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: jeromedwight
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. I-commit at i-push. Pumunta sa **Actions** tab ng repo, i-run manually ang workflow ("Run workflow") para sa unang pagkakataon.
4. Maghintay ng ~1-2 minuto — lalabas na ang animated snake sa profile README mo automatically (dahil naka-link na sa `output` branch).

</details>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,100:1a1a2e&height=3&width=100%&animation=twinkling" width="100%"/>
</div>

## 🎮 Beyond the Code

<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=16&pause=1500&color=94A3B8&center=true&vCenter=true&width=700&lines=Playing+NBA+2K22+on+my+MSI+Thin+15;Into+music+-+Daniel+Caesar+on+repeat;Debugging+by+day%2C+gaming+by+night" alt="Beyond the code typing SVG" />

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,100:1a1a2e&height=3&width=100%&animation=twinkling" width="100%"/>
</div>

## 📫 Let's Connect

<div align="center">

📧 **Email:** 09368072602tm@gmail.com
💼 **LinkedIn:** Coming soon
🌐 **Portfolio:** Coming soon

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=100&section=footer&animation=twinkling" width="100%"/>

</div>
