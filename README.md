<!-- Erol Külüşlü · GitHub profile README -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=2,12,20,24&height=190&section=header&text=Erol%20K%C3%BCl%C3%BC%C5%9Fl%C3%BC&fontSize=61&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20Applied%20AI%20%C2%B7%20MSc%20Research&descAlignY=62&descSize=17&descColor=ccd6f6" width="100%" alt="Erol Külüşlü — Software Engineer, Applied AI, MSc Research" />

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&pause=1600&color=64FFDA&center=true&vCenter=true&width=750&lines=From+mobile+apps+to+multimodal+models.;Sometimes+the+baseline+wins.+That's+research." alt="From mobile apps to multimodal models. Sometimes the baseline wins. That's research." />

  <br />
  <a href="https://linkedin.com/in/erolkuluslu"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:erol.kuluslu@agu.edu.tr"><img alt="Email" src="https://img.shields.io/badge/Email-444?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://medium.com/@erolkuluslusoftware"><img alt="Medium" src="https://img.shields.io/badge/Writing-12100E?style=flat-square&logo=medium&logoColor=white" /></a>
</div>

About
I'm a software engineer and MSc student in Computer Engineering at Abdullah Gül University. I'm currently in Germany for my Erasmus+ master's thesis at Hochschule Aalen.

My background includes Flutter apps, backend services, document processing, and workflow automation. My research focuses on machine learning for images, structured data, and retrieval systems. I've also taught Python and AI to students, educators, and public-sector groups.

I like work that moves between building a system, testing how well it works, and explaining the result.
What I'm working on now
Multimodal learning for battery manufacturing · MSc thesis, Hochschule Aalen
2026–2027 · Ongoing research

I'm studying how microscopy images and material measurements can support prediction and analysis in battery manufacturing.
- Data: light microscopy, surface roughness (WLI), SEM cross-sections, four-point-probe measurements, and related sample metadata.
- Current work: dataset inspection, sample alignment, segmentation checks, and image/measurement feature analysis.
- Model plan: compare image-only and measurement-only baselines with feature concatenation and attention-based fusion.
- Constraint: the image data is available; additional time-series data is not yet ready. I am checking data quality and target definitions before reporting model results.
The project is part of my thesis, “Developing a Multi-Modal Machine Learning Model for Manufacturing Data.” The working repository and raw research data are not public.
Selected projects
01 · MNEME — Temporal Knowledge Graph RAG
Python · Sentence-BERT · BM25 · NetworkX · Louvain · LLMs

A research implementation for querying personal documents with time-aware retrieval and citations. I developed it with collaborators as part of our work on LLM memory and retrieval.
- Builds a chunk-level knowledge graph with typed relationships and time metadata.
- Combines dense retrieval and BM25 with Reciprocal Rank Fusion (RRF).
- Uses query routing, graph communities, hub/bridge nodes, and year-aware citation checks.
- Includes evaluation scripts, tests, and a research manuscript.
Code and architecture
02 · CM-JEPA — RGB / Infrared Fusion
PyTorch · Self-supervised learning · JEPA · Computer vision

I tested whether JEPA-based cross-modal learning could improve lightweight object detection and segmentation from paired visible and infrared images.
- Evaluated 6,025 aligned image pairs from M3FD, MSRS, and RoadScene.
- Compared RGB-only, infrared-only, average fusion, attention variants, and CM-JEPA gate-blend.
- Measured downstream results with YOLO11n (detection) and U-Net / MobileNetV2 (segmentation).
- Finding: average fusion performed better overall. Its segmentation mIoU was 0.5551, compared with 0.4774 for gate-blend. This result informs the next model design.
Reproducible notebook, metrics, and paper
03 · ILA — Mobile applications and workflow automation
Flutter · Dart · BLoC · OAuth2 · AWS · OCR / NLP

At International Labour Association (ILA), I worked on two mobile applications and software used to support international education and Erasmus+ activities.
- Built and maintained app features for project discovery, applications, profiles, and related workflows.
- Developed an OCR-based travel-document flow: mobile capture → text extraction → field validation → backend processing.
- Worked on document/entity extraction, cloud functions, and internal automations to reduce manual steps.
- Contributed across mobile, backend, and integration tasks in an international team.
Some of this work is proprietary, so I describe my contribution without publishing the source code. ILA Portal on the App Store · ILA
04 · MuloAD — Cross-population cancer classification
GraphSAGE · VCDN · Biomedical machine learning

Research on colorectal-cancer classification from gut-microbiome data. I adapted graph-based learning and multimodal integration methods and evaluated how models transfer between populations.
- Compared models under cross-population evaluation rather than relying only on within-dataset splits.
- An earlier experiment reached ROC-AUC 0.808 for Japan → India transfer.
- This is an experiment-specific result, not a general clinical performance claim.
05 · Mnemosyne Agents — Multi-agent orchestration
Python · Agent orchestration · Monitoring · Async workflows

An experimental agent platform with an orchestrator for text, audio, image, and video tasks. The repository includes prompt chaining, vector memory, caching, retry policies, rate limiting, and monitoring components.
<details>
<summary><b>More code and experiments</b></summary>


- Image Classifier: image preprocessing, embeddings, dataset cleanup, PyTorch training, and a Gradio interface.
- Expense Tracking: a Flutter app used to explore BLoC state management and expense visualization.
- ISIC 2024 experiments: compared image/tabular late fusion and optimization strategies for skin-lesion classification.
</details>

Engineering and research toolkit
Area	Tools and methods
Software	Python, Dart, Flutter, REST APIs, Git, CI/CD
Cloud and automation	AWS Lambda, serverless workflows, OCR, information extraction, n8n
Machine learning	PyTorch, scikit-learn, computer vision, self-supervised learning, multimodal fusion
LLM systems	RAG, hybrid search, knowledge graphs, LLM agents, retrieval evaluation


Teaching and international work
- AI education, Kayseri Bilişim Akademisi: planned and delivered applied AI, ML, and Python training. I worked with students, teachers, and public institutions.
- ILA, Amsterdam: gained software engineering experience in a team working on international education and mobility projects.
- Erasmus+ and volunteering: participated in international projects and volunteering activities across Europe. My current Erasmus mobility is based at Aalen University.
I enjoy technical conversations as much as the implementation work. Teaching has made me more careful about explaining assumptions, limitations, and results.
Activity
<div align="center">
  <img src="https://raw.githubusercontent.com/erolkuluslu/erolkuluslu/output/snake.svg" alt="GitHub contribution snake" width="95%" />
</div>

<div align="center">
  <sub>Based in Aalen, Germany · From Kayseri, Türkiye</sub><br />
  <sub><a href="https://github.com/erolkuluslu">GitHub</a> · <a href="https://linkedin.com/in/erolkuluslu">LinkedIn</a> · <a href="mailto:erol.kuluslu@agu.edu.tr">Email</a></sub>
</div>
