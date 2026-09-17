<!-- ============================================================= -->
<!--  HASHITH ALAKUNTA — GITHUB PROFILE README                     -->
<!--  Theme: dark luxury / purple · indigo · violet                -->
<!-- ============================================================= -->

<div align="center">

<img width="100%" src="assets/banner.svg" alt="Hashith Alakunta — Inference and ML Systems Engineering"/>


<br/><br/>

<a href="https://github.com/hashithhh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&pause=1200&color=A78BFA&center=true&vCenter=true&width=760&lines=Inference+%26+ML+Systems+Engineer+in+training;Multi-Agent+RAG+%E2%80%A2+CUDA+%E2%80%A2+Model+Evaluation;B.Tech+CSE+%E2%80%A2+SRM+University+AP+%E2%80%A2+2023%E2%80%932027;I+build+systems+that+make+models+run+faster" alt="typing"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/B.Tech%20CSE-SRM%20University%20AP-6D28D9?style=flat-square&labelColor=0D1117&logo=graduation-cap&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/Class%20of-2027-7C3AED?style=flat-square&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/UROP-Undergraduate%20Research-8B5CF6?style=flat-square&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Andhra%20Pradesh-India-4C1D95?style=flat-square&labelColor=0D1117&logo=googlemaps&logoColor=A78BFA"/>

<br/><br/>

<a href="https://nexus-research.me"><img src="https://img.shields.io/badge/Live%20Project-nexus--research.me-8B5CF6?style=for-the-badge&labelColor=0D1117&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/hashithhh"><img src="https://img.shields.io/badge/LinkedIn-Connect-6366F1?style=for-the-badge&labelColor=0D1117&logo=linkedin&logoColor=white"/></a>
<a href="mailto:REPLACE_WITH_YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-Reach%20Out-7C3AED?style=for-the-badge&labelColor=0D1117&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/hashithhh"><img src="https://img.shields.io/badge/GitHub-Follow-4C1D95?style=for-the-badge&labelColor=0D1117&logo=github&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=hashithhh&label=Profile%20Views&color=8B5CF6&style=flat-square"/>
<img src="https://img.shields.io/github/followers/hashithhh?label=Followers&style=flat-square&color=7C3AED&labelColor=0D1117"/>
<img src="https://img.shields.io/github/stars/hashithhh?label=Total%20Stars&style=flat-square&color=6D28D9&labelColor=0D1117"/>

</div>

---

## About

I am a final-year Computer Science undergraduate at **SRM University AP**, working toward
**inference and ML systems engineering** — the layer between a trained model and a system that
actually serves it under load.

My work sits across three areas. **Applied AI**: a deployed multi-agent retrieval platform with
causal attribution and a self-recalibrating ranker. **Research**: symbolic prediction of GPU peak
memory for transformer workloads, carried out as undergraduate research. **Systems**: the CUDA,
kernel and serving-path work I am moving into next, because I would rather understand why a model
is slow than add another wrapper on top of someone else's API.

I ship production software as well as experiments — full-stack internship work in Node and React,
computer-vision pipelines in PyTorch, containerised deployments on Azure — and I care about the
engineering discipline around models: reproducibility, evaluation that is not self-congratulatory,
and tests that fail for the right reason.

**Open to:** inference / ML systems engineering roles · applied AI engineering · research
internships in efficient ML · open-source collaboration on serving and evaluation infrastructure.

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,cpp,ts,js,c&theme=dark"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark"/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,mongodb,redis&theme=dark"/>

**ML & Systems**

<img src="https://skillicons.dev/icons?i=pytorch,opencv,sklearn,anaconda&theme=dark"/>

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=azure,docker,git,github,linux,vscode,obsidian&theme=dark"/>

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
| :--- | :---: | :--- |
| **Retrieval & RAG Systems** | Advanced | Multi-agent orchestration, hybrid `pgvector` + BM25 retrieval, leave-one-out causal attribution, self-recalibrating rankers |
| **Deep Learning (Vision)** | Proficient | PyTorch and OpenCV; real-time crowd monitoring; spatio-temporal attention architectures for human activity recognition |
| **Model Evaluation & Reproducibility** | Proficient | Paper reproduction under test, regression suites for model behaviour, documenting inconsistencies in published work |
| **Interpretable ML** | Proficient | VAE-based compression with stacking ensembles, SHAP attribution — published at IEEE ETAACT 2026 |
| **GPU Memory & Performance Modelling** | Developing | Symbolic prediction of transformer peak memory (UROP research); Nsight-based profiling |
| **Inference Engineering** | Learning | Paged KV cache, continuous batching, quantisation, CUDA / Triton kernels — active build track |

</div>

---

## Featured Projects

<details open>
<summary><b>&nbsp;Nexus — Multi-Agent Research OS</b></summary>

<br/>

A deployed multi-agent retrieval platform that answers research questions over a document corpus
and, critically, explains *why* it answered that way — each claim is attributed back to the
retrieved passages that caused it, using leave-one-out ablation rather than post-hoc citation.

| | |
| :--- | :--- |
| **Stack** | Python · PostgreSQL + `pgvector` · BM25 · Docker · Azure · React |
| **Scale** | Multi-agent planner / retriever / synthesiser loop over a chunked document corpus |
| **Performance** | Hybrid dense + lexical retrieval path; self-recalibrating ranker that reweights on observed answer quality |
| **Evaluation** | Leave-one-out causal attribution; benchmark run on a 20-question self-authored evaluation set |
| **Security** | Containerised deployment, environment-scoped secrets, no third-party data egress beyond the model provider |
| **Impact** | Live at [nexus-research.me](https://nexus-research.me) — the reference implementation for how I think retrieval systems should be audited |
| **Repository** | [`hashithhh/nexus`](https://github.com/hashithhh) |

Nexus exists because most RAG systems cannot tell you which retrieved chunk was load-bearing for
an answer. Ablating each retrieved passage and measuring the change in the generated answer turns
attribution into a measurement instead of a claim. The evaluation set is small and self-authored —
stated plainly here rather than dressed up as a benchmark result.

</details>

<details>
<summary><b>&nbsp;STAD-ConvBi-LSTM — Paper Reproduction Under Test</b></summary>

<br/>

A from-scratch reproduction of a published spatio-temporal attention architecture for human
activity recognition, built as a test-covered codebase rather than a notebook.

| | |
| :--- | :--- |
| **Stack** | PyTorch · OpenCV · NumPy · pytest |
| **Dataset** | UCF11 human action recognition |
| **Architecture** | Convolutional feature extraction → bidirectional LSTM → spatio-temporal attention |
| **Testing** | 18 pytest cases covering tensor shapes, attention masking and training-step invariants |
| **Finding** | 7 internal inconsistencies documented between the published description and a reproducible implementation |
| **Repository** | [`hashithhh/stad-convbi-lstm`](https://github.com/hashithhh) |

The interesting output of this project was not the accuracy number — it was the list of places
where the paper could not be reproduced as written. Reproduction is an engineering skill, and
writing tests around a research model is how you find out whether you actually understood it.

</details>

<details>
<summary><b>&nbsp;SYMPEAK — Symbolic GPU Peak-Memory Prediction <sub>(UROP · in progress)</sub></b></summary>

<br/>

Undergraduate research on predicting the peak GPU memory of a transformer workload symbolically —
from architecture, sequence length and batch configuration — instead of discovering it by running
the job and watching it OOM.

| | |
| :--- | :--- |
| **Stack** | Python · PyTorch · CUDA memory instrumentation · symbolic modelling |
| **Goal** | A parametric envelope for activation + KV-cache + optimiser-state memory across configurations |
| **Why** | Scheduling and batching decisions in an inference server need a memory answer *before* the allocation, not after |
| **Status** | Active undergraduate research (UROP) — results in progress, nothing published yet |
| **Repository** | Private until results are ready |

This feeds directly into the inference-engine track below: a scheduler that knows the memory
envelope of a request can pack the GPU far more aggressively than one that guesses.

</details>

<details>
<summary><b>&nbsp;Interpretable Wine Quality Prediction <sub>(IEEE ETAACT 2026)</sub></b></summary>

<br/>

| | |
| :--- | :--- |
| **Stack** | Python · scikit-learn · PyTorch · SHAP |
| **Method** | Variational autoencoder compression feeding a stacking ensemble, with SHAP attribution over the learned representation |
| **Contribution** | Interpretability retained through a compressed latent space rather than sacrificed for accuracy |
| **Venue** | Published — IEEE ETAACT 2026 |

</details>

---

## Currently Building

Four systems projects are in active development. They are listed here for direction, not as
finished work — repositories go public when there is something worth reading.

<div align="center">

| Project | What It Is | State |
| :--- | :--- | :---: |
| **Ledger** | Self-maintaining evaluation engine — OpenTelemetry traces scored, human-approved into regression cases, enforced as a CI gate | In progress |
| **Crucible** | ~100M-parameter language model trained from scratch, with ablations and a scaling study against Chinchilla | In progress |
| **Conduit** | Inference engine — paged KV cache, continuous batching, quantisation, symbolic memory scheduler | Planned |
| **Ignis** | CUDA / Triton kernels — staged matmul toward cuBLAS parity, fused softmax and layernorm, FlashAttention-style attention, Nsight roofline analysis | Planned |

</div>

---

## Experience

#### AI Intern &nbsp;·&nbsp; Infosys Springboard
`Feb 2026 — Apr 2026`

Built **DeepVision**, a real-time crowd monitoring pipeline, as part of the Springboard AI
internship programme.

- Implemented detection and tracking over live video streams in PyTorch and OpenCV
- Tuned the inference path for real-time throughput on constrained hardware
- Handled the full loop: data preparation, model integration, evaluation, demo delivery

<img src="https://img.shields.io/badge/PyTorch-0D1117?style=flat-square&logo=pytorch&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/OpenCV-0D1117?style=flat-square&logo=opencv&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/Computer%20Vision-0D1117?style=flat-square&logo=python&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/Real--Time%20Inference-0D1117?style=flat-square&logo=nvidia&logoColor=A78BFA"/>

<br/>

#### Full Stack Developer Intern &nbsp;·&nbsp; Trinwo Solutions
`May 2025 — Jul 2025`

Built a resume-to-portfolio application end to end on a Node/Express stack.

- Designed and implemented the parsing pipeline that turns an uploaded resume into structured data
- Built the REST API and the React front end that renders generated portfolios
- Shipped to a live environment and iterated on real user feedback

<img src="https://img.shields.io/badge/Node.js-0D1117?style=flat-square&logo=nodedotjs&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/Express-0D1117?style=flat-square&logo=express&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=A78BFA"/>
<img src="https://img.shields.io/badge/REST%20APIs-0D1117?style=flat-square&logo=fastapi&logoColor=A78BFA"/>

---

## Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| **IEEE Publication** | Interpretable wine quality prediction — VAE compression, stacking ensemble, SHAP attribution · IEEE ETAACT 2026 |
| **Undergraduate Research (UROP)** | Selected for undergraduate research on symbolic GPU peak-memory prediction for transformer workloads |
| **Production Deployment** | Nexus multi-agent research platform, live at nexus-research.me |
| **LeetCode 50 Days Badge** | 2026 · 315+ problems solved · longest streak 75 days |
| **Academic Record** | Intermediate MPC 9.1 · SSC 9.8 |

</div>

<!-- Add anything else here: hackathon placements, paper presentations, scholarships. -->

---

## Certifications

<!-- ============================================================================= -->
<!--  FILL THIS IN. Delete every provider block you do not actually hold.          -->
<!--  Do not leave a badge here for a certificate you cannot produce on request.   -->
<!-- ============================================================================= -->

<div align="center">

**Amazon Web Services**

<img src="https://img.shields.io/badge/AWS-Certificate%20Name-0D1117?style=for-the-badge&logo=amazonwebservices&logoColor=A78BFA&labelColor=4C1D95"/>

**Oracle**

<img src="https://img.shields.io/badge/Oracle-Certificate%20Name-0D1117?style=for-the-badge&logo=oracle&logoColor=A78BFA&labelColor=4C1D95"/>

**NPTEL**

<img src="https://img.shields.io/badge/NPTEL-Course%20Name-0D1117?style=for-the-badge&logo=googlescholar&logoColor=A78BFA&labelColor=4C1D95"/>

**Cisco**

<img src="https://img.shields.io/badge/Cisco-Certificate%20Name-0D1117?style=for-the-badge&logo=cisco&logoColor=A78BFA&labelColor=4C1D95"/>

</div>

---

## Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/hashithhh/">
  <img src="https://img.shields.io/badge/LeetCode-315%2B%20Solved-0D1117?style=for-the-badge&logo=leetcode&logoColor=A78BFA&labelColor=4C1D95"/>
</a>

<!-- Add GeeksforGeeks / HackerRank / CodeChef badges here only once those profiles
     are real and the numbers on them help you. Checked Sept 2026: no GfG profile
     under this handle; CodeChef shows 21 solved, which reads worse than silence. -->
<br/><br/>

<img src="https://leetcard.jacoblin.cool/hashithhh?theme=dark&font=JetBrains%20Mono&ext=heatmap" alt="LeetCode stats"/>

</div>

---

## GitHub Analytics

<div align="center">

<img width="88%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=hashithhh&theme=github_dark" alt="Profile summary"/>

<br/>

<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=hashithhh&theme=github_dark" alt="Stats"/>
<img height="190" src="https://streak-stats.demolab.com?user=hashithhh&hide_border=true&background=0D1117&stroke=4C1D95&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA&sideLabels=C4B5FD&currStreakNum=EDE9FE&sideNums=EDE9FE&dates=6D28D9" alt="Streak"/>

<br/>

<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=hashithhh&theme=github_dark" alt="Repos per language"/>
<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=hashithhh&theme=github_dark" alt="Most committed language"/>

<br/>

<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=hashithhh&theme=github_dark&utcOffset=5.5" alt="Productive time"/>

</div>

---

## Contribution Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hashithhh/hashithhh/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hashithhh/hashithhh/output/github-snake.svg"/>
  <img alt="snake animation" src="https://raw.githubusercontent.com/hashithhh/hashithhh/output/github-snake.svg"/>
</picture>

</div>

<!-- Rendered by .github/workflows/snake.yml, which writes the SVGs to the `output` branch. -->

---

## Current Focus

```yaml
name: Hashith Alakunta
role: Inference & ML Systems Engineering
location: Andhra Pradesh, India

learning:
  - CUDA and Triton kernel programming
  - Paged KV cache, continuous batching, quantisation
  - Transformer training dynamics and scaling laws
  - GPU profiling with Nsight Compute

building:
  - Ledger    # self-maintaining evaluation engine with a CI gate
  - Crucible  # ~100M parameter LM from scratch + scaling study

exploring:
  - Symbolic prediction of GPU peak memory (UROP research)
  - Serving-path bottlenecks in multi-agent retrieval systems

open_to:
  - Inference / ML systems engineering roles
  - Applied AI engineering roles
  - Research internships in efficient ML
  - Open-source work on serving and evaluation infrastructure
```

---

## Connect

<div align="center">

<a href="mailto:REPLACE_WITH_YOUR_EMAIL"><img src="https://img.shields.io/badge/Gmail-0D1117?style=for-the-badge&logo=gmail&logoColor=A78BFA&labelColor=4C1D95"/></a>
<a href="https://www.linkedin.com/in/hashithhh"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=A78BFA&labelColor=4C1D95"/></a>
<a href="https://github.com/hashithhh"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=A78BFA&labelColor=4C1D95"/></a>
<a href="https://nexus-research.me"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=A78BFA&labelColor=4C1D95"/></a>

</div>

---

<div align="center">

<i>The model is the easy part. Making it run is the engineering.</i>

<img width="100%" src="assets/footer.svg" alt=""/>

</div>
