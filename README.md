<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║  Hey, you found the source code! Here's a secret terminal for curious devs:  ║
╠══════════════════════════════════════════════════════════════════════════════╣
║  $ josh --help                                                               ║
║                                                                              ║
║  Usage: josh [COMMAND] [OPTIONS]                                             ║
║                                                                              ║
║  Commands:                                                                   ║
║    research     Show current research projects                               ║
║    train        Start training a model (requires GPU)                        ║
║    coffee       Current caffeine level: ████████░░ 80%                       ║
║    papers       Papers read this month: 12                                   ║
║    hire         Download resume and start interview process                  ║
║                                                                              ║
║  $ josh hire --role="ML Engineer" --start="Summer 2026"                      ║
║  > Initializing hiring pipeline...                                           ║
║  > Loading resume from https://jlowe.ai/resume                               ║
║  > Candidate looks promising! Schedule interview? [Y/n]                      ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->

<!-- Header Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21&height=180&section=header&text=Josh%20Lowe&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=ML%20Engineer%20|%20Researcher%20|%20Builder&descAlignY=52&descAlign=50"/>
</p>

<!-- Animated Typing -->
<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=13547a&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=60&lines=M.S.+Computer+Science+%40+UCF;Research+Assistant+at+AI+MIND+Lab+%40+UCF" alt="Typing SVG" />
  </a>
</p>

<!-- Social Badges -->
<p align="center">
  <a href="https://jlowe.ai"><img src="https://img.shields.io/badge/jlowe.ai-13547a?style=for-the-badge&logo=safari&logoColor=white"/></a>
  <a href="https://linkedin.com/in/joshrlowe"><img src="https://img.shields.io/badge/LinkedIn-13547a?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:joshlowe.cs@gmail.com"><img src="https://img.shields.io/badge/Email-80d0c7?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://ucf.joinhandshake.com/profiles/joshrlowe"><img src="https://img.shields.io/badge/Handshake-80d0c7?style=for-the-badge&logo=handshake&logoColor=white"/></a>
</p>


---

### About Me

```python
class JoshLowe:
    def __init__(self):
        self.location = "Orlando, FL"
        self.education = ["M.S. CS @ UCF", "B.S. CS @ FSU", "B.S. Math @ FSU"]
        self.role = "Research Assistant at AI MIND Lab @ UCF"
        
    def current_research(self):
        return "Fine-tuning VLMs for automated cardiac cine-MRI analysis"
    
    def projects(self):
        return {
            "research": [
                "CardioVLM", 
                "Automated Program Repair", 
                "Federated Learning Privacy", 
                "NutriLLaVA"
                ],
            "web_apps": [
              "jlowe.ai", 
              "SWESphere", 
              "Ace Service Group", 
              "Mailsweep"
              ],
            "systems": [
              "jarvis", 
              "Barstool Scheduler", 
              "C Shell"
              ]
        }
```

---

### Current Research

<table>
<tr>
<td width="50%" valign="top">

#### CardioVLM
**Automated Cardiac MRI Analysis with Vision-Language Models**

Building VQA systems that enable natural language queries about cardiac function and pathology using the ACDC dataset.

`Hugging Face` `Medical Imaging` `VLMs` `VQA`

</td>
<td width="50%" valign="top">

#### [Automated Program Repair](https://www.jlowe.ai/projects/llm-apr-benchmark)
**Which LLM Fixes It Best? A Comparative Study**

Custom APR tool that accepts a codebase path, error message, and model selection to automatically diagnose and fix software bugs. Benchmarks state-of-the-art LLMs from Anthropic, OpenAI, Google, and xAI on repair success across diverse bug categories to provide actionable guidelines for model selection.

`Python` `OpenAI API` `Anthropic API` `Google Gemini API`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Dynamic APR on SWE-bench Lite](https://github.com/joshrlowe/swebench-lite-dynamic-apr)
**Cross-model automated program repair**

Research experiment that runs dynamic, cross-model APR on SWE-bench Lite. Continues the comparative LLM-repair line with a public, reproducible pipeline.

`Python` `SWE-bench` `LLMs`

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

---

### Past Research

<table>
<tr>
<td width="50%" valign="top">

#### [Federated Learning Privacy](https://www.jlowe.ai/projects/mia-mitigation-in-fed-learning)
**Evaluating Mitigation Strategies for Membership Inference Attacks in Federated Learning**

Implements federated learning to train Wide ResNet 28-4 on CIFAR-100 and evaluates differential privacy as a defense against membership inference attacks. Produced counterintuitive findings: DP caused accuracy to drop 86% while attack success increased from 70.6% to 84.3% on overfit models.

`Python` `PyTorch` `Flower` `Opacus` `ART` `NumPy` `Scikit-learn` `Ray`

</td>
</tr>
</table>

---

### Projects

<table>
<tr>
<td width="50%" valign="top">

#### [NutriLLaVA](https://www.jlowe.ai/projects/nutrillava)
**Multimodal AI for Personalized Recipes**

![Completed](https://img.shields.io/badge/Completed-22C55E?style=flat-square) ![Featured](https://img.shields.io/badge/Featured-FFD700?style=flat-square)

Large Multimodal Model app that generates personalized recipes from fridge/pantry photos based on dietary goals. Comparative study between LLaVA 1.5 (7B) and 1.6 (34B) revealed upgrading improved success rates from 32.5% to 77.5%, with ingredient hallucination as the key differentiator.

`Python` `PyTorch` `Hugging Face` `LLaVA 1.6` `Gradio` `Pillow` `Google Colab`

</td>
<td width="50%" valign="top">

#### [Ace Service Group LLC](https://www.jlowe.ai/projects/ace-service-group)
**Professional Marketing Website**

![Completed](https://img.shields.io/badge/Completed-22C55E?style=flat-square)

Full-stack marketing website for a PA construction company featuring a striking 3D animated playing card logo using Three.js and React Three Fiber. Includes complete admin dashboard with portfolio management, dynamic services, and contact form submissions with IP-based rate limiting.

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Three.js` `GSAP` `NextAuth` `Tailwind`

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

#### [jlowe.ai](https://www.jlowe.ai/projects/jlowe-ai)
**Personal Portfolio**

![In Progress](https://img.shields.io/badge/In_Progress-80d0c7?style=flat-square) ![Featured](https://img.shields.io/badge/Featured-FFD700?style=flat-square)

Full-stack portfolio with immersive "Supernova" space theme featuring Three.js animated starfield and GSAP scroll animations. Includes admin CMS, blog with comments/likes, newsletter subscriptions, and comprehensive testing with 256 E2E tests across 4 browsers using Playwright.

`Next.js` `TypeScript` `Prisma` `Three.js` `GSAP` `Playwright` `Jest` `Tailwind`

</td>
<td width="50%" valign="top">

#### [SWESphere](https://www.jlowe.ai/projects/swesphere)
**Full-Stack Social Media Platform**

![In Progress](https://img.shields.io/badge/In_Progress-80d0c7?style=flat-square)

Comprehensive Twitter-like platform spanning SvelteKit web, FastAPI backend with Celery workers, and Flutter mobile app with Clean Architecture. Features real-time WebSocket notifications, 12+ language i18n, and security-focused implementation with CSP, CSRF protection, and rate limiting.

`FastAPI` `SvelteKit` `Flutter` `PostgreSQL` `Redis` `Celery` `Docker` `Nginx`

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

#### [Barstool Scheduler](https://www.jlowe.ai/projects/barstool-scheduler)
**Linux Kernel Module**

![Completed](https://img.shields.io/badge/Completed-22C55E?style=flat-square)

Multi-part Linux kernel programming project demonstrating custom system call implementation, kernel module development, and concurrent programming. Features bar simulation where customers are seated at tables managed by a waiter kthread with mutex synchronization and procfs state exposure.

`C` `Linux Kernel API` `Procfs` `Kthreads` `Mutex` `Make`

</td>
<td width="50%" valign="top">

#### [C Shell](https://www.jlowe.ai/projects/c-shell)
**Custom Unix Shell**

![Completed](https://img.shields.io/badge/Completed-22C55E?style=flat-square)

Unix shell implementation with tokenization, environment variable expansion, tilde expansion, and PATH-based executable resolution. Supports I/O redirection, command piping (up to two pipes), background process execution, and built-in commands including cd, echo, jobs, and exit.

`C` `GCC` `Make` `POSIX` `Fork` `File Descriptors`

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

#### [jarvis](https://github.com/joshrlowe/jarvis)
**Self-hosted personal AI assistant**

![In Progress](https://img.shields.io/badge/In_Progress-80d0c7?style=flat-square)

Monorepo for a local assistant: LangGraph gateway, memory, voice, local-model routing, MCP skills, and a sandbox. Contract-first (Pydantic contracts, generated TypeScript, mock servers). Still early.

`Python` `TypeScript` `LangGraph` `pnpm` `uv` `Docker`

</td>
<td width="50%" valign="top">

#### [Mailsweep](https://github.com/joshrlowe/email-cleaner)
**Local-first Gmail cleanup**

![In Progress](https://img.shields.io/badge/In_Progress-80d0c7?style=flat-square)

Gmail sweeper that works from metadata only, with undoable batches and an optional Claude natural-language bar. Next.js app, BullMQ worker, Prisma/Postgres, Redis.

`TypeScript` `Next.js` `Prisma` `BullMQ` `Gmail API`

</td>
</tr>
</table>

<p align="center">
  <a href="https://jlowe.ai/projects">
    <img src="https://img.shields.io/badge/View_All_Projects-jlowe.ai-13547a?style=for-the-badge"/>
  </a>
</p>

---

### Tech Stack

<details>
<summary><b>Machine Learning & AI</b></summary>
<br>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black"/>
</p>
</details>

<details>
<summary><b>Web Development</b></summary>
<br>
<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
</p>
</details>

<details>
<summary><b>Cloud & DevOps</b></summary>
<br>
<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</p>
</details>

<details>
<summary><b>Tools & Databases</b></summary>
<br>
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white"/>
</p>
</details>

---

### Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=joshrlowe&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=80d0c7&line=80d0c7&point=FFFFFF&area=true&area_color=13547a" alt="Contribution Graph"/>
</p>

<!-- Snake animation (uncomment after running the workflow on GitHub)
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/joshrlowe/joshrlowe/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/joshrlowe/joshrlowe/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/joshrlowe/joshrlowe/output/github-snake.svg" />
  </picture>
</p>
-->

---

### Education & Experience

```
EDUCATION
├── M.S. Computer Science @ UCF (2025-2027)
│   └── 4.0 GPA • Research Assistant • AI MIND Lab
├── B.S. Computer Science @ FSU (2019-2023)
└── B.S. Mathematics @ FSU (2019-2023)

EXPERIENCE
├── Research Assistant @ UCF AI MIND Lab
├── QA Engineer Intern @ CSC
└── Tech Lead @ Google DSC FSU
```

<details>
<summary><b>Leadership Experience</b></summary>
<br>

- **Tech Lead** @ Google Developer Student Clubs - Mentored 40+ students
- **Union Board Policy Chairman** @ FSU SGA - Redesigned 100+ page policy manual
- **VP of Programming** @ IFC FSU - Managed 1,610 members, co-created $5K scholarship
- **AWS Certified Developer - Associate**

</details>

---

<p align="center">
  <i>Let's build something amazing together.</i>
</p>

<p align="center">
  <a href="https://jlowe.ai">
    <img src="https://img.shields.io/badge/Visit_My_Portfolio-jlowe.ai-13547a?style=for-the-badge"/>
  </a>
</p>

---

<!-- Footer Wave -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21&height=100&section=footer"/>
</p>

<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║  You made it to the end of the source! Here's your reward:                   ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║  $ josh train --model="CardioVLM" --epochs=100                               ║
║                                                                              ║
║  Epoch [1/100]: loss=2.847 | acc=0.12 | lr=1e-4                              ║
║  Epoch [25/100]: loss=0.892 | acc=0.67 | lr=1e-4                             ║
║  Epoch [50/100]: loss=0.341 | acc=0.84 | lr=1e-5                             ║
║  Epoch [100/100]: loss=0.089 | acc=0.94 | lr=1e-6                            ║
║                                                                              ║
║  ✓ Training complete! Model saved to ./checkpoints/cardio_vlm_best.pt        ║
║  ✓ Validation accuracy: 94.2%                                                ║
║  ✓ Ready for deployment                                                      ║
║                                                                              ║
║  Fun facts about Josh:                                                       ║
║  - Mass Effect is the greatest trilogy of all time                           ║
║  - I ran the St. Pete Marathon in 3:51 - always trying to PR                 ║
║  - My attention span for research papers: ∞                                  ║
║  - My attention span for documentation: ~15 minutes                          ║
║                                                                              ║
║  Secret link: https://jlowe.ai/secret (just kidding... or am I?)             ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->
