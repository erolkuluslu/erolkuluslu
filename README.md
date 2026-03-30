<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<!--                        EROL KÜLÜŞLÜ · GITHUB PROFILE                       -->
<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<!-- ── HEADER ──────────────────────────────────────────────────────────────── -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=2,12,20,24&height=220&section=header&text=Erol%20Külüşlü&fontSize=68&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Researcher%20%E2%80%94%20Computer%20Vision%20%C2%B7%20Applied%20ML%20%C2%B7%20Biomedical%20AI&descAlignY=60&descSize=17&descColor=ccd6f6" width="100%"/>
</div>

<br/>

<!-- ── TYPING ANIMATIONS ───────────────────────────────────────────────────── -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&pause=1200&color=64FFDA&center=true&vCenter=true&width=720&lines=Training+loss%3A+converging+%E2%86%98+%E2%9C%93;Architecture%3A+multimodal+%28RGB+%2B+IR+%2B+caffeine%29;Currently+exploring+latent+space...;Self-supervised+by+curiosity+%E2%80%94+fine-tuned+by+deadlines;Software+Engineer+%C2%B7+MSc+Researcher+%C2%B7+AI+Educator" alt="Research Typing SVG" />
</div>

---

<div align="center">
  <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="500" alt="AI animation"/>
</div>

---
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,20,24&height=120&section=footer&text=the%20model%20is%20still%20training...&fontSize=22&fontColor=64ffda&animation=twinkling&fontAlignY=65" width="100%"/>
</div>

<!-- ── MODEL CARD ──────────────────────────────────────────────────────────── -->
## 🧬 Model Card

<div align="center">

| Parameter | Value |
|:---|:---|
| **Current Epoch** | MSc in ECE · Abdullah Gül University · Est. 2027 |
| **Loss** | Converging ↘ (slowly, like all good research) |
| **Status** | 🟢 Active · Multiple experiments running in parallel |

</div>

---

<!-- ── ABOUT ME ─────────────────────────────────────────────────────────────── -->
# About Me

I'm **Erol Külüşlü**, a **Software Engineer** and **MSc Researcher** in Computer Vision & Applied ML at Abdullah Gül University, currently working as an **AI Specialist** at Kayseri Bilişim Akademisi.

I build and study **end-to-end intelligent systems** — spanning self-supervised multimodal learning, graph neural networks for biomedical AI, retrieval-augmented generation, and production-grade software engineering.

**Highlights:**
- Designing **CM-JEPA**: a self-supervised RGB-IR fusion framework using JEPA-based latent prediction, VICReg regularization, and gradient-based structural consistency.
- Adapting **MuloAD (GraphSAGE + VCDN)** for colorectal cancer classification from gut microbiome data — best result: cross-population AUC = 0.808 (JPN → IND).
- Built **MNEME**: a temporal knowledge graph RAG system over 187 documents across four domains — submitted for journal publication.
- Designing and delivering **AI/ML training programs** for university students, teachers, and public institutions.
- Built production NER pipelines, OCR benchmarking frameworks, and serverless AWS infrastructure across 2.5 years at ILA Amsterdam.
- Writing on **Medium** about LLMs, context engineering, and applied AI systems.
- International experience: Erasmus+ exchange in the **Netherlands** + volunteering across **10+ countries**.

> Building systems that understand context, retain knowledge, and make intelligence accessible — at every scale.

[Check out my resume](https://github.com/user-attachments/files/26358050/Erol_Kuluslu_CV.pdf)
---

<!-- ── RESEARCH AREAS ───────────────────────────────────────────────────────── -->
## 🔬 Research Areas


<div align="center">
<table>
<tr>
<td align="center" width="220">

**Computer Vision**

RGB-IR multimodal fusion<br/>
Self-supervised representation learning<br/>
Domain adaptation · Segmentation<br/>
*CM-JEPA (JEPA + VICReg + grad loss)*

</td>
<td align="center" width="220">

**Biomedical AI**

Graph neural networks for drug repositioning<br/>
Gut microbiome → cancer classification<br/>
GraphSAGE · VCDN · Multi-omics<br/>
*MSc Thesis + ECE648 Project*

</td>
<td align="center" width="220">

**Knowledge & Retrieval**

Temporal knowledge graph RAG<br/>
Community detection · Hub/bridge analysis<br/>
Sentence-BERT · Louvain · RRF<br/>
*MNEME — submitted to journal*

</td>
</tr>
<tr>
<td align="center" width="220">

**Optimization Dynamics**

Adaptive learning rate methods<br/>
Gradient starvation in multimodal nets<br/>
AdaGrad · RMSprop · Adam · AdamW<br/>
*ECE567 systematic study*

</td>
<td align="center" width="220">

**AI Systems & Agents**

RAG pipelines · LLM orchestration<br/>
n8n automation · Agentic workflows<br/>
Context engineering · Prompt design<br/>
*Published on Medium*

</td>
<td align="center" width="220">

**Software Engineer**

End-to-end Flutter apps · BLoC · OAuth2<br/>
AWS Lambda · CI/CD · Serverless<br/>
NER pipelines · OCR benchmarking<br/>
*3 years @ ILA Amsterdam*

</td>
</tr>
</table>
</div>

---

<!-- ── ACTIVE EXPERIMENTS ──────────────────────────────────────────────────── -->
## Active Experiments

```python
experiments = {
    "CM-JEPA": {
        "desc":   "Cross-modal RGB-IR fusion via JEPA-based latent prediction",
        "loss":   "L_JEPA + α·L_VIC + γ·L_grad",
        "eval":   ["YOLOv8-Nano", "MobileNetV2/U-Net"],
        "data":   ["M3FD", "MSRS", "LLVIP", "TNO"],
        "status": "🟡 Active Research",
    },
    "MuloAD-CRC": {
        "desc":   "GraphSAGE + VCDN for colorectal cancer · gut microbiome",
        "result": "Cross-population AUC = 0.808 (JPN → IND)",
        "key_biomarker": "Peptostreptococcus stomatis",
        "status": "🟠 Preparing Journal Submission",
    },
    "MNEME": {
        "desc":   "Temporal KG-RAG · 187 docs · 4 domains · 2020–2025",
        "stack":  "Sentence-BERT + Louvain + RRF",
        "mrr":    0.85,
        "status": "🟢 Submitted",
    },
    "Optimizer-Skin": {
        "desc":   "Late-fusion multimodal optimizer comparison · ISIC 2024",
        "configs": ["Uniform Adam", "Decoupled LR", "Asymm SGD+NAG/Adam", "AdaGrad"],
        "status": "🔵 In Progress",
    },
}
```

---

<!-- ── CURRENT FOCUS ────────────────────────────────────────────────────────── -->
# 🧩 Current Focus

🔹 **AI Research** → Self-supervised multimodal fusion (CM-JEPA), GNN-based drug repositioning, optimization dynamics in deep learning.  
🔹 **AI Engineering** → RAG, graph-based retrieval, LLM agents, inference optimization.  
🔹 **Mobile** → High-quality mobile apps and websites.  
🔹 **Cloud** → Serverless pipelines, cost-efficient deployment, scalable AI workflows.  
🔹 **Research & Writing** → Context engineering, multi-agent systems, SLM potential.

---

<!-- ── TECH STACK ───────────────────────────────────────────────────────────── -->
# ⚙️ Tech Stack

<div align="center">

**Core ML & Research**

[![Python](https://skillicons.dev/icons?i=python)](https://python.org)
[![PyTorch](https://skillicons.dev/icons?i=pytorch)](https://pytorch.org)
[![TensorFlow](https://skillicons.dev/icons?i=tensorflow)](https://tensorflow.org)
[![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=for-the-badge)](https://huggingface.co)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![NetworkX](https://img.shields.io/badge/NetworkX-Graph-orange?style=for-the-badge)](https://networkx.org)

</div>

### AI & Data
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FCC624?logo=huggingface&logoColor=black)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Graph%20Based-blue?style=flat-square&logo=knowledgebase)

<div align="center">

**Cloud & Infrastructure**

[![AWS](https://skillicons.dev/icons?i=aws)](https://aws.amazon.com)
[![Docker](https://skillicons.dev/icons?i=docker)](https://docker.com)
[![GithubActions](https://skillicons.dev/icons?i=githubactions)](https://github.com/features/actions)
[![Linux](https://skillicons.dev/icons?i=linux)](https://linux.org)

</div>

### Cloud & Data Pipelines
![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS%20Lambda-F29111?logo=awslambda&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-Pipelines-purple?style=flat-square)

<div align="center">

**Mobile & Frontend**

[![Flutter](https://skillicons.dev/icons?i=flutter)](https://flutter.dev)
[![Dart](https://skillicons.dev/icons?i=dart)](https://dart.dev)
[![Figma](https://skillicons.dev/icons?i=figma)](https://figma.com)
[![Next.js](https://skillicons.dev/icons?i=nextjs)](https://nextjs.org)

</div>


<div align="center">

**Tooling & Workflows**

[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com)
[![Jupyter](https://skillicons.dev/icons?i=jupyter)](https://jupyter.org)
[![VSCode](https://skillicons.dev/icons?i=vscode)](https://code.visualstudio.com)

</div>

### 🛠 Workflow & Tools
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-000000?logo=githubactions&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white)
![Agile](https://img.shields.io/badge/Agile-Scrum-0A66C2)

---

<!-- ── GITHUB STATS ─────────────────────────────────────────────────────────── -->
# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=erolkuluslu&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda&icon_color=64ffda&text_color=ccd6f6&rank_icon=github" height="175" alt="GitHub Stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=erolkuluslu&theme=tokyonight&hide_border=true&background=0d1117&ring=64ffda&fire=ff6b6b&currStreakLabel=64ffda" height="175" alt="Streak Stats"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=erolkuluslu&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda&text_color=ccd6f6&langs_count=8" height="150" alt="Top Languages"/>
</p>

---

<!-- ── CONTRIBUTION SNAKE ──────────────────────────────────────────────────── -->
## 🐍 Contribution Graph

<div align="center">

> *"Every green square is a step in gradient descent."*

<!--
  To enable the snake animation, create this file in your profile repo:
  .github/workflows/snake.yml

  name: Generate Snake
  on:
    schedule: [{ cron: "0 0 * * *" }]
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: dist/snake.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

![snake svg](https://github.com/erolkuluslu/erolkuluslu/blob/output/snake.svg)

</div>

---

<!-- ── INTERNATIONAL FOOTPRINT ─────────────────────────────────────────────── -->
## 🌍 International Footprint

```
🇹🇷 Kayseri, Turkey     — AGU · Research base 
🇳🇱 Amsterdam, NL       — ILA · 3 years Software engineering
🌐 10+ countries        — EVS/ESC volunteering across Europe
```

---

<!-- ── FEATURED WRITING ─────────────────────────────────────────────────────── -->
# ✍️ Featured Writing

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1200&color=36BCF7&center=true&vCenter=true&width=800&lines=📚+I+write+about+AI%2C+Flutter%;✨+Exploring+LLMs%2C+RAG%2C+and+Scalable+App+Design;🚀+Turning+Ideas+Into+Working+Systems" alt="Writing Typing Animation" />
</p>

<div align="center">

<img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="40px">
<i>Welcome to my writing space where engineering meets creativity.</i>

---

### 📖 Latest Medium Articles

<a href="https://medium.com/@erolkuluslusoftware/the-best-flutter-app-architecture-exists-does-it-🤔-6a8f765d5632" target="_blank">
  <img src="https://img.shields.io/badge/The%20Best%20Flutter%20App%20Architecture%20Exists%20(Does%20it%3F🤔)-%2302569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter Article"/>
</a>

<a href="https://medium.com/@erolkuluslusoftware/context-engineering-the-new-paradigm-every-developer-should-know-4e87e4d028b9" target="_blank">
  <img src="https://img.shields.io/badge/Context%20Engineering%3A%20The%20New%20Paradigm%20Every%20Developer%20Should%20Know-%23FFD700?style=for-the-badge&logo=readme&logoColor=black" alt="Context Engineering Article"/>
</a>

[![Medium Profile](https://img.shields.io/badge/All_Articles_→_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@erolkuluslusoftware)

</div>

<br/>

✨ *I actively publish on Medium about* **Flutter, large language models, and AI** — turning research concepts into practical, scalable, and developer-friendly systems.

🔗 [🌐 View All Articles on Medium](https://medium.com/@erolkuluslusoftware)


<!-- ── CONNECT ──────────────────────────────────────────────────────────────── -->
# 🌐 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/erolkuluslu/"><img src="https://skillicons.dev/icons?i=linkedin" width="48"/></a>
  <a href="https://medium.com/@erolkuluslusoftware"><img src="https://img.icons8.com/ios-filled/50/000000/medium-logo.png" width="48"/></a>
  <a href="mailto:erolkuluslusoftware@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" width="48"/></a>
  <a href="https://github.com/erolkuluslu"><img src="https://skillicons.dev/icons?i=github" width="48"/></a>
</p>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/erolkuluslu)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/erolkuluslu)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@erolkuluslusoftware)
[![Email](https://img.shields.io/badge/AGU_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:erol.kuluslu@agu.edu.tr)

</div>

---

<!-- ── QUOTE & VISITOR COUNT ───────────────────────────────────────────────── -->
<p align="center">
  <i>"Code is temporary, but architecture and ideas last."</i>
</p>

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical"/>
</p>

<p align="center">
  <img src="https://visitcount.itsvg.in/api?id=erolkuluslu&icon=0&color=6" alt="Visitor Count"/>
</p>

---

<!-- ── FOOTER ──────────────────────────────────────────────────────────────── -->

<!--
  Profile repo : erolkuluslu/erolkuluslu
  Snake action : see .github/workflows/snake.yml comment above
  Stat theme   : tokyonight — keep consistent across all cards
-->
