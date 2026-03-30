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

--

<br/>

✨ *I actively publish on Medium about* **Flutter, and AI** — turning research concepts into practical, scalable, and developer-friendly systems.

🔗 [🌐 View All Articles on Medium](https://medium.com/@erolkuluslusoftware)


<!-- ── CONNECT ──────────────────────────────────────────────────────────────── -->
# 🌐 Connect with Me

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
---


