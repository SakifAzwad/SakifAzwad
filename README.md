<h1 align="center">Hi, I'm Sakif Azwad 👋</h1>

<p align="center">
  <b>Full-Stack Developer who also ships AI</b><br/>
  Next.js · TypeScript · Node.js · PostgreSQL · Python · ICPC problem solver
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1200&color=2F81F7&center=true&vCenter=true&width=560&lines=I+build+web+apps+people+actually+use.;Correctness+first%2C+then+speed.;2%2C200%2B+problems+solved+%C2%B7+410%2B+day+streak.;Open+to+remote+roles+worldwide." alt="Typing intro" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Roles-2ea44f?style=for-the-badge" alt="Open to remote roles" />
  <a href="https://sakif-azwad.web.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/sakifazwad/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sakifazwad18@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://codeforces.com/profile/Raftyy"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
</p>

---

```ts
const sakif = {
  role:      "Full-Stack Developer (+ AI)",
  location:  "Chattogram, Bangladesh · UTC+6",
  building:  "MeetReady v2: a Calendly-style scheduler, rebuilt solo and live on Vercel",
  web:       ["Next.js", "React", "TypeScript", "Node.js", "Express", "PostgreSQL", "MongoDB"],
  ai:        ["Python", "PyTorch", "TensorFlow", "OpenCV"],
  solved:    "2,200+ problems · 410+ day Codeforces streak",
  openTo:    "Remote full-stack roles, worldwide",
};
```

## 📖 The short story

I placed **6th at the National Informatics Olympiad in 2014**, and I've been hooked on hard problems ever since. At university I competed seriously, earned an **Honorable Mention at ICPC Asia Dhaka 2022**, and later served as contest secretary of IIUC's programming club, writing the problems and test cases for others to struggle with.

Somewhere along the way I realized I wanted my code used by *people*, not just judges. So I started building for the web: booking systems, e-commerce, dashboards. For our undergraduate thesis, my team built **HyFiNet**, a fire-detection model that now runs as a live demo.

Most recently I rebuilt **MeetReady**, a 2024 team project, solo and from scratch. It's [live now](https://meetreadyv2.vercel.app), built on what competitive programming taught me: **correctness first, then speed.**

---

## 🚀 Featured Work

### 📅 MeetReady v2 &nbsp;·&nbsp; *Calendly-style meeting scheduler* &nbsp;🟢 Live

Hosts set event types and weekly availability and share a link. Guests book in their own timezone.

- **Double booking is impossible:** prevented at three layers (app re-check, per-host advisory lock, and a PostgreSQL exclusion constraint)
- Secure guest cancel/reschedule via hashed manage tokens, `.ics` calendar invites, and email notifications
- Google login with owner-scoped authorization, IDOR-tested CRUD, and open-redirect protection
- Property-based tests (fast-check) plus race tests on real Postgres, with CI on GitHub Actions
- Custom "Daylight" design system with a timezone- and DST-aware booking flow
- 🚧 In development: AI-powered scheduling features

<p>
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" />
  <img src="https://img.shields.io/badge/Better_Auth-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

<a href="https://meetreadyv2.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-Try_it-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live demo" /></a>
<a href="https://github.com/SakifAzwad/MeetReady-V2"><img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source code" /></a>

### 🔥 HyFiNet &nbsp;·&nbsp; *Fire detection with deep learning*

A CNN with a custom attention module that detects fire in images, built for our undergraduate thesis.

- Attention module, model, and training pipeline written from scratch
- Ablation study documented in the repo, showing what each component contributes
- Deployed as an interactive **Gradio** demo on **Hugging Face Spaces**: upload an image, get a prediction

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Computer_Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
</p>

<a href="https://huggingface.co/spaces/Fire-Detection-Lab/HyFiNet"><img src="https://img.shields.io/badge/Live_Demo-Try_it-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Live demo" /></a>
<a href="https://github.com/SakifAzwad/Hyfinet"><img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source code" /></a>

### 🧰 More projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| **MeetReady v1** | Interview booking system with conflict-safe scheduling, email reminders, analytics dashboard *(team project, 2024)* | Next.js · TypeScript · Firebase · JWT | [Live](https://meet-ready.vercel.app/) · [Code](https://github.com/SakifAzwad/Meet-Ready) |
| **Raf Hotel** | Hotel booking with a calendar UI, live availability and pricing | React · Node · Express · MongoDB · JWT | [Live](https://raf-hotel.web.app/) · [Client](https://github.com/SakifAzwad/Raf-Hotel-Client) · [Server](https://github.com/SakifAzwad/Raf-Hotel-Server) |
| **Raf Tech** | Tech-gadget store with full CRUD cart, user accounts and order history | React · Node · Express · MongoDB · JWT | [Live](https://raf-tech-d3ff8.web.app/) · [Client](https://github.com/SakifAzwad/Raf-Tech-Client) · [Server](https://github.com/SakifAzwad/Raf-Tech-Server) |

---

## 🛠️ Tech Stack

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=ts,js,py,cpp,c&theme=dark" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,html,css&theme=dark" />

**Backend & Databases**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,firebase&theme=dark" />

**AI / ML**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv&theme=dark" />

**Tools & Platforms**<br/>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,vercel,netlify,wordpress&theme=dark" />

**🌱 Currently leveling up with** (through MeetReady v2)<br/>
<img src="https://img.shields.io/badge/PostgreSQL_+_Neon-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" />
<img src="https://img.shields.io/badge/Better_Auth-111111?style=flat-square" />
<img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" />
<img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white" />
<img src="https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white" />
<img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

---

## 🧠 Problem Solving

<p>
  <a href="https://codeforces.com/profile/Raftyy">
    <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3DRaftyy&query=%24.result%5B0%5D.maxRating&label=Codeforces%20Max%20Rating&style=for-the-badge&logo=codeforces&color=1F8ACB" alt="Codeforces max rating" />
  </a>
  <img src="https://img.shields.io/badge/Daily%20Streak-410%2B%20days%20🔥-orange?style=for-the-badge" alt="410+ day streak" />
</p>

| Platform | Solved |
|---|---|
| [Codeforces](https://codeforces.com/profile/Raftyy) | **1,500+** |
| UVa Online Judge | **500+** |
| [CodeChef](https://www.codechef.com/users/raftyy_13) | **200+** |
| **Total** | **2,200+** |

## 🏆 Achievements

- 🥇 **Honorable Mention**: ICPC Asia Dhaka Regional Contest, 2022
- 🏆 **Champion**: CCE Fest IIUC Programming Contest, 2022
- 🏆 **Champion**: IIUC Intra-University Programming Contest, 2021
- 🥉 **2nd Runner-Up**: IIUC Intra-University Programming Contest, 2022
- 🎖️ **6th Place**: National Informatics Olympiad, 2014

---

## ⚡ Beyond the code

- 🔥 Solved at least one problem every day for **410+ days straight**
- 🧮 **Perfect score** in SAT Math, and taught math from Grade 8 to A-Level through university
- 👨‍🏫 Teaching Assistant for *Computer Programming 1* at IIUC for two semesters
- 🧩 Wrote contest problems and test cases as IIUC's programming club contest secretary
- 🎓 BSc in Computer Science & Engineering, International Islamic University Chittagong (2020–2024)

---

<p align="center">
  <b>Hiring for a remote full-stack role?</b> Let's talk.<br/><br/>
  <a href="mailto:sakifazwad18@gmail.com">sakifazwad18@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/sakifazwad/">LinkedIn</a> ·
  <a href="https://sakif-azwad.web.app/">Portfolio</a>
</p>
