<div align="center">

<!-- Dynamic Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Puneeth%20Hegde&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20Problem%20Solver&descAlignY=58&descColor=a78bfa&animation=fadeIn" width="100%" />

<!-- Typing Animation -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+AI+that+serves+real+people+%F0%9F%8C%B1;From+farmlands+to+fintech+%F0%9F%8C%8D;Offline+AI+%7C+Computer+Vision+%7C+Full-Stack;Turning+ideas+into+impact+%F0%9F%9A%80" alt="Typing SVG" /></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/puneeth-hegde)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/puneeth-hegde)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

</div>

---

## 🧠 About Me

```python
class PuneethHegde:
    def __init__(self):
        self.name        = "Puneeth Hegde"
        self.role        = "AI Engineer & Full-Stack Developer"
        self.passion     = "Building AI that solves real-world problems"
        self.focus       = ["LLMs & RAG", "Computer Vision", "Full-Stack Apps"]
        self.languages   = ["Python", "TypeScript", "Dart", "SQL"]
        self.currently   = "Open to roles in AI/ML & Full-Stack Development"

    def philosophy(self):
        return "Technology should empower the underserved, not just the privileged."
```

I build **end-to-end AI systems** — from training custom vision models to deploying intelligent full-stack apps. My projects span **agriculture AI**, **fintech inclusion**, **offline rural assistants**, **security systems**, and **satellite image analysis**. I care deeply about building tech with purpose.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌱 Digital Krishi Officer
> *AI-powered agricultural advisor for Indian farmers*

An intelligent full-stack advisory system that combines **custom computer vision** (MobileNetV2 on PlantVillage), **RAG with ChromaDB**, and **live API tools** into a single multilingual farmer assistant.

**Highlights:**
- 🗣️ Strict multilingual responses: English, Kannada, Malayalam
- 📸 Diagnoses **38 plant disease classes** across 14 species
- 🌦️ Real-time weather + AGMARKNET mandi price tools
- 🧠 Llama 3.1 via Groq as the central orchestrator
- 🐳 Deployed on Hugging Face Spaces + Vercel

**Stack:** `Python` `FastAPI` `PyTorch` `ChromaDB` `Next.js` `Groq`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/puneeth-hegde/digital-krishi-officer)

</td>
<td width="50%" valign="top">

### 💸 FinVerse
> *AI-powered financial inclusion platform*

A production-grade fintech prototype that empowers the **unbanked** with AI credit scoring (alternative data), a Llama 3 financial advisor, P2P lending, micro-savings goals, and 3D portfolio dashboards.

**Highlights:**
- 🤖 Proprietary credit scoring (300–850) using rent, utility & mobile data
- 💬 Real-time Groq-powered financial advisor chat
- 🪩 React Three Fiber 3D dashboard visualizations
- 🔐 Full Supabase auth + RLS + real-time DB
- 🌐 Live on Netlify

**Stack:** `Next.js 14` `TypeScript` `Supabase` `Groq` `React Three Fiber` `Tailwind`

[![Demo](https://img.shields.io/badge/Live_Demo-00C7B7?style=flat-square&logo=netlify)](https://finverse-prototype.netlify.app/)
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/puneeth-hegde/finverse)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗣️ Sakhi Sahayak
> *Offline AI village assistant — zero internet required*

A **fully offline, privacy-first Flutter app** built for rural India. The entire AI pipeline (STT → Intent → LLM → TTS) runs on-device using Whisper Tiny Q8, LLaMA 1B Q4, and native Android JNI — no cloud, no data leakage.

**Highlights:**
- 🎙️ On-device Whisper STT via JNI (PCM16 → Float32)
- 🧠 Quantized LLaMA 1B simplifies tasks into 3–4 clear steps
- 🖼️ Pictogram-based visual guidance for low-literacy users
- 🔒 Zero external API calls — 100% private
- 📱 Works on any Android device (4GB RAM+)

**Stack:** `Flutter` `Kotlin` `Whisper` `LLaMA` `JNI` `Android`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/puneeth-hegde/sakhi-sahayak)

</td>
<td width="50%" valign="top">

### 🛡️ SENTINEL v5.0
> *Dual-camera AI security system*

A real-time security system with **face recognition**, **body language analysis**, **weapon detection**, and **cross-camera tracking** — all running on a GTX 1650 at 12–15 FPS.

**Highlights:**
- 👤 InsightFace recognition in under 3 seconds
- 🏃 YOLOv8 + ByteTrack for person tracking
- 🤸 MediaPipe body language & threat scoring
- 🔫 Weapon detection via YOLO
- 🔔 Real-time audio alerts with loitering detection

**Stack:** `Python` `PyTorch` `YOLOv8` `InsightFace` `MediaPipe` `CUDA`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/puneeth-hegde/sentinel)

</td>
</tr>
<tr>
<td width="50%" colspan="2" valign="top">

### 🛰️ Land Use & Land Cover Change Detection (LULC)
> *Deep learning satellite image segmentation — Team Project*

A U-Net semantic segmentation pipeline built in **TensorFlow/Keras** that classifies satellite imagery into LULC classes (vegetation, water, urban, barren) and tracks **temporal land-use changes** through an interactive Dash dashboard.

**My Role:** Data preprocessing, U-Net training pipeline, model integration, and visualizations

**Highlights:**
- 🗺️ Pixel-wise multi-class segmentation from satellite rasters
- 📉 Cross-year change detection with area delta analysis
- 📊 Interactive Dash dashboard for exploring regional trends
- 🧪 Dice/IoU metrics, augmentation, configurable architecture

**Stack:** `TensorFlow` `Keras` `U-Net` `NumPy` `OpenCV` `Plotly Dash` `Rasterio`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/puneeth-hegde/land-use-land-cover)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Full-Stack**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**Infra & Tools**

![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=puneeth-hegde&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=puneeth-hegde&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=puneeth-hegde&theme=tokyonight&hide_border=true" />
</div>

---

## 🌟 What Drives Me

> *"The best AI isn't the most powerful — it's the one that reaches those who need it most."*

From building an app that helps a farmer in Karnataka identify crop disease without internet access, to creating a platform that gives unbanked individuals a financial identity — every project I build is rooted in **real-world impact**. I'm constantly exploring the intersection of **AI, accessibility, and inclusion**.

---

<div align="center">

**Thanks for stopping by! If my work resonates with you, let's connect. 🤝**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
