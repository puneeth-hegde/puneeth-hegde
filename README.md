# Hi, I'm Puneeth Hegde 👋

I'm an AI Engineer and Full-Stack Developer passionate about building intelligent systems that solve real-world problems. My work spans computer vision, LLM-powered applications, offline AI, and full-stack development.

---

## 🚀 Projects

### 🏠 AI-Powered Smart Home Security System &nbsp;`Final Year Major Project — VTU 2025`
> A context-aware, multi-camera home security system that runs 4 AI models simultaneously on consumer hardware with zero cloud dependency.

- **76% reduction in false alarms** through session-based tracking (one alert per person per visit)
- Dual-camera pipeline: YOLOv8n + ByteTrack for detection, InsightFace for face recognition (88% accuracy at 70° angles)
- Behavioral threat analysis using MediaPipe (33 skeletal keypoints) — loitering, pacing, aggressive stances
- Multi-signal threat fusion: Pose (30%) + Movement (30%) + Temporal (20%) + Weapon detection (20%)
- Cross-camera identity linking: tracks a person from gate to door seamlessly
- 15–18 FPS running all models simultaneously on GTX 1650, fully local
- **My role:** Pose Estimation & Behavior Analysis module
- **Team:** Abhishek M, Adithya B Hanglur, Puneeth, Sarvan D Suvarna, Shamith Vakwady

`Python` `PyTorch` `YOLOv8` `InsightFace` `MediaPipe` `ByteTrack` `OpenCV` `CUDA`

---

### 🌱 Digital Krishi Officer
> An AI-powered agricultural advisory system for Indian farmers with multilingual support, plant disease diagnosis, and real-time data tools.

- Custom-trained **MobileNetV2** on the PlantVillage dataset — identifies **38 disease classes** across 14 crop species
- RAG pipeline using **ChromaDB** + Sentence Transformers for local agricultural knowledge retrieval
- Live tools for real-time weather and AGMARKNET mandi (wholesale market) prices
- Strictly multilingual responses in English, Kannada, and Malayalam
- **Llama 3.1 via Groq** as the central orchestrating agent
- Deployed on Hugging Face Spaces (backend) + Vercel (frontend)

`Python` `FastAPI` `PyTorch` `ChromaDB` `Next.js` `Groq API`

---

### 💸 FinVerse
> A full-stack AI-driven financial inclusion platform prototype for the unbanked, with credit scoring, P2P lending, and a financial literacy hub.

- Proprietary **AI credit scoring** (300–850) using alternative data: rent, utility payments, mobile usage
- Real-time financial advisor chat powered by **Groq's Llama 3**
- P2P lending marketplace with risk-level classification and full Supabase RLS
- Interactive savings goal tracker and financial literacy quiz module
- **React Three Fiber** 3D portfolio dashboard visualizations
- Live demo deployed on Netlify

`Next.js 14` `TypeScript` `Supabase` `Groq` `React Three Fiber` `Tailwind CSS`

🔗 [Live Demo](https://finverse-prototype.netlify.app/)

---

### 🗣️ Sakhi Sahayak — Offline AI Village Assistant
> A fully offline, privacy-first Flutter app for rural India where the entire AI pipeline runs on-device — no internet, no cloud, no data leakage.

- On-device **Whisper Tiny Q8** for speech-to-text via native Android JNI (PCM16 → Float32)
- **LLaMA 1B Q4** (quantized) converts complex queries into 3–4 simple actionable steps
- Pictogram-based visual guidance designed for low-literacy users
- Intent detection distinguishes Assist queries from incident Reports
- Offline TTS for voice output — zero external API calls
- Built with Flutter + Kotlin, JNI bindings for all ML models

`Flutter` `Kotlin` `Whisper` `LLaMA` `JNI` `Android`

---

### 🛡️ SENTINEL v5.0
> A dual-camera AI security system with face recognition, body language analysis, weapon detection, and cross-camera tracking.

- **InsightFace** face recognition with voting mechanism to prevent misclassifications (<3 sec)
- **YOLOv8 + ByteTrack** for multi-person detection and persistent ID tracking
- **MediaPipe** body language analysis with loitering and face-hidden detection
- Weapon detection via YOLO, real-time audio TTS alerts
- Threat scoring, snapshot management, and live enrollment (press 'E')
- Runs at 12–15 FPS on GTX 1650

`Python` `PyTorch` `YOLOv8` `InsightFace` `MediaPipe` `CUDA`

---

### 🛰️ Land Use & Land Cover Change Detection (LULC) &nbsp;`Team Project`
> A deep learning semantic segmentation system for analyzing satellite imagery and detecting temporal land-use changes.

- **U-Net** (TensorFlow/Keras) for pixel-wise multi-class segmentation — vegetation, water, urban, barren
- Cross-year change detection with class-wise area delta analysis
- Interactive **Plotly Dash** dashboard for exploring regional trends
- Trained with Dice/IoU metrics and configurable augmentation
- **My role:** Data preprocessing, U-Net training pipeline, model integration, and visualizations
- **Team:** Puneeth Hegde, Sarvan D Suvarna, Shamith Vakwadey, Abhishek M

`TensorFlow` `Keras` `U-Net` `NumPy` `OpenCV` `Plotly Dash` `Rasterio`

---

## 🛠️ Tech Stack

**Languages:** Python · TypeScript · Dart · SQL

**AI / ML:** PyTorch · TensorFlow · OpenCV · YOLOv8 · InsightFace · MediaPipe · Whisper · LLaMA · ChromaDB · Sentence Transformers

**Full-Stack:** Next.js · FastAPI · Flutter · Supabase · React Three Fiber · Tailwind CSS

**Tools & Infra:** Git · Docker · Vercel · Hugging Face Spaces · CUDA · Linux

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=puneeth-hegde&show_icons=true&theme=default&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=puneeth-hegde&layout=compact&theme=default&hide_border=true&langs_count=8" height="160"/>
</div>

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/puneeth-hegde)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:your@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/puneeth-hegde)
