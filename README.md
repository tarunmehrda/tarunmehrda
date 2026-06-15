<!--
═══════════════════════════════════════════════════════════════
  TARUN MEHARDA · GitHub Profile README
  Accent color: #00C7B7  ·  Theme: tokyonight  ·  Vibe: clean-futuristic
  ⚡ Headline feature: live contribution-snake (setup steps at bottom)
═══════════════════════════════════════════════════════════════
-->

<!-- ░░░ HERO ░░░ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,18,24,30&height=210&section=header&text=Tarun%20Meharda&fontSize=78&fontColor=fff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20·%20ML%20Scientist%20·%20Data%20Scientist&descAlignY=58&descSize=20" width="100%"/>

<a href="https://tarun-meharda-portfolio.netlify.app/" target="_blank"><img src="https://custom-icon-badges.demolab.com/badge/Portfolio-Visit-00C7B7?style=for-the-badge&logo=globe&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/tarun-meharda-62878a34a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:tarunmehrda@gmail.com"><img src="https://img.shields.io/badge/Gmail-Reach%20Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/tarunmehrda" target="_blank"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=00C7B7&center=true&vCenter=true&width=720&height=50&lines=Turning+raw+data+into+real+intelligence;Neural+Nets+%7C+NLP+%7C+Computer+Vision+%7C+GenAI;Shipping+production-ready+ML+systems;Always+building.+Always+learning." alt="Typing SVG"/>

<br/>

<img src="https://komarev.com/ghpvc/?username=tarunmehrda&label=Profile%20Views&color=00C7B7&style=flat-square" alt="views"/>
<img src="https://img.shields.io/github/followers/tarunmehrda?label=Followers&style=flat-square&color=00C7B7" alt="followers"/>
<img src="https://img.shields.io/badge/Based%20in-Pilani,%20India%20🇮🇳-00C7B7?style=flat-square" alt="location"/>
<img src="https://img.shields.io/badge/Open%20to-Work%20🟢-00C7B7?style=flat-square" alt="open to work"/>

</div>

---

## ⚡ `whoami`

# .github/workflows/snake.yml
# Generates the contribution-snake animation used in the profile README.
# Runs every day + on every push to main, and can be triggered manually.

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # daily at 00:00 UTC
  workflow_dispatch:        # lets you run it manually from the Actions tab
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5
    steps:
      - name: Generate snake SVGs
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/snake.svg
            dist/snake-dark.svg?palette=github-dark&color_snake=#00C7B7

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<table>
<tr>
<td width="50%" valign="top">

#### 🧪 Currently building
- 🔥 RAG-based document Q&A system
- 🎨 Image generation with Stable Diffusion
- 🤖 Multi-agent AI workflows
- ⚙️ Automated end-to-end ML pipeline

</td>
<td width="50%" valign="top">

#### 🌱 Currently learning
- 🧠 LLM fine-tuning at scale (LoRA / QLoRA)
- 🔎 Neural Architecture Search
- 📦 MLOps with Docker + MLflow
- 🛰️ Agentic AI & tool-use patterns

</td>
</tr>
</table>

---

## 🛠️ Tech Arsenal

<div align="center">

**🤖 ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)

**🧬 NLP / GenAI**

![Hugging Face](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=for-the-badge&logoColor=black)
![LangChain](https://img.shields.io/badge/🦜%20LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)

**📊 Data Science**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

**💻 Languages & Deploy**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📈 [Stock & Crypto Price Predictor](https://github.com/tarunmehrda/Real-Time-Stock-Crypto-Minute-Level-Price-Prediction)
> Minute-level forecasting on volatile markets with a real-time streaming + retraining pipeline.

`LSTM` · `TensorFlow` · `Streamlit`

**🎯 87% accuracy** on live crypto data · interactive dashboard · continuous retraining

</td>
<td width="50%" valign="top">

### 🤖 [CoderBuddy — AI Coding Assistant](https://github.com/tarunmehrda/CoderBuddy)
> GPT-powered, context-aware code generation with a clean React front end.

`OpenAI` · `FastAPI` · `React`

**⚡ ~40% faster** on repetitive tasks · multi-language · real-time analysis

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 [Healthcare Premium Prediction](https://github.com/tarunmehrda/Healthcare-Premium-Prediction)
> Production-deployed regression system with heavy feature engineering and validation.

`Scikit-learn` · `XGBoost` · `Flask`

**🎯 92% accuracy** · full EDA · ensemble methods · live API

</td>
<td width="50%" valign="top">

### 🧠 [More dropping soon…](https://github.com/tarunmehrda)
> Always one experiment ahead.

`RAG` · `Stable Diffusion` · `Multi-Agent`

**🔭 In the lab:** doc Q&A · image gen · automated ML framework

</td>
</tr>
</table>

---

## 📊 The Numbers

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=tarunmehrda&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C7B7&icon_color=00C7B7&text_color=FFFFFF&rank_icon=github" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=tarunmehrda&theme=tokyonight&hide_border=true&background=0D1117&ring=00C7B7&fire=00C7B7&currStreakLabel=00C7B7" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tarunmehrda&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C7B7&text_color=FFFFFF&langs_count=8" width="40%"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=tarunmehrda&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&title_color=00C7B7" width="98%"/>

</div>

---

## 🐍 Watch my commits get eaten

<!-- ░░░ HEADLINE UNIQUE FEATURE — contribution snake (auto-generated by GitHub Action) ░░░ -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tarunmehrda/tarunmehrda/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tarunmehrda/tarunmehrda/output/snake.svg"/>
  <img alt="contribution snake animation" src="https://raw.githubusercontent.com/tarunmehrda/tarunmehrda/output/snake.svg"/>
</picture>

<sub>🟢 The snake slithers across my contribution graph and devours each commit — regenerated automatically every day. <em>(Setup steps are at the bottom of this file.)</em></sub>

</div>

---

## 🧭 How I Build

<div align="center">

```mermaid
graph LR
    A[📥 Data] --> B[🧹 Clean]
    B --> C[🔍 EDA]
    C --> D[⚙️ Features]
    D --> E[🤖 Model]
    E --> F[🎯 Train]
    F --> G[✅ Evaluate]
    G --> H{Good?}
    H -->|No| E
    H -->|Yes| I[🚀 Deploy]
    I --> J[📊 Monitor]
    J --> B
    style A fill:#FF6B6B,stroke:#fff,color:#000
    style E fill:#45B7D1,stroke:#fff,color:#000
    style I fill:#00C7B7,stroke:#fff,color:#000
```

</div>

---

## ✍️ Writing & Sharing

<div align="center">

| 📝 Topic | 🔗 Platform | 📅 Status |
|:---|:---:|:---:|
| Deep Dive into Transformer Architecture | Medium | ✅ Published |
| Building Production ML Pipelines | Dev.to | ✅ Published |
| Fine-tuning LLMs: A Practical Guide | Medium | ✍️ In Progress |
| MLOps Best Practices | Dev.to | ✍️ In Progress |

</div>

---

## 💬 Dev quote of the day

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="random dev quote"/>

</div>

---

## 🤝 Let's build something

<div align="center">

I'm open to **AI/ML research**, **data science consulting**, **AI product builds**, and **technical writing**.

<a href="https://tarun-meharda-portfolio.netlify.app/" target="_blank"><img src="https://img.shields.io/badge/🌐%20Portfolio-Explore-00C7B7?style=for-the-badge"/></a>
<a href="https://www.linkedin.com/in/tarun-meharda-62878a34a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin"/></a>
<a href="mailto:tarunmehrda@gmail.com"><img src="https://img.shields.io/badge/Gmail-Email%20Me-EA4335?style=for-the-badge&logo=gmail"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,18,24,30&height=130&section=footer&text=Thanks%20for%20stopping%20by!&fontSize=30&fontColor=fff&animation=twinkling&fontAlignY=68"  width="100%"/>

<strong>⚡ "Data is the new oil — I'm here to refine it into intelligence."</strong>

<sub>Built with 🧠 AI · ❤️ passion · ☕ coffee</sub>

</div>

<!--
═══════════════════════════════════════════════════════════════
  🐍 SNAKE ANIMATION — ONE-TIME SETUP (delete this comment after)
  1. This file must live in a repo named exactly: tarunmehrda/tarunmehrda
  2. Create file:  .github/workflows/snake.yml   (contents provided alongside this README)
  3. GitHub → repo Settings → Actions → General → Workflow permissions
     → enable "Read and write permissions" → Save
  4. Run it once:  Actions tab → "Generate Snake" → Run workflow
  5. Done — it now refreshes daily and the images above go live.
═══════════════════════════════════════════════════════════════
-->
