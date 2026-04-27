<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=160&section=header&text=Puneeth%20Hegde&fontSize=48&fontColor=e2e8f0&fontAlignY=55&desc=AI%20Engineer%20%E2%80%A2%20Full-Stack%20Developer&descAlignY=75&descColor=94a3b8&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/puneeth-hegde)
 
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/puneeth-hegde)
 
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:puneethgshede@gmail.com)

</div>

-----

I build **end-to-end AI systems** — from fine-tuning computer vision models and designing RAG pipelines to shipping production full-stack applications. I focus on building systems that work in the real world, not just in notebooks.

-----

## Projects

**GNSS Weather Prediction API**   `final year internship project 2026`

An end-to-end rainfall forecasting system using GNSS-derived atmospheric signals fused with NASA meteorological data to predict precipitation 6 hours ahead. Deployed as a live REST API on **HuggingFace Spaces**.

> CNN-LSTM · Temporal Fusion Transformer · FastAPI · Docker · HuggingFace Spaces

- Trained on **15 years of hourly data (2010–2025)** from the IISC GPS station (Zenith Total Delay, Precipitable Water Vapor) merged with NASA POWER variables — 134,715 rows, 13 features, 48-hour lookback window
- **Two-stage architecture:** a CNN-LSTM classifier first decides if it will rain, then a separate CNN-LSTM regressor predicts the amount in mm/hr — handles severe class imbalance without inflating false alarms
- Also trained a custom **Temporal Fusion Transformer** (GRN + Variable Selection + Multi-Head Attention) for Stage 1; final prediction blends CNN (10%) and TFT (90%) outputs
- Live endpoint: [`/predict/demo-storm`](https://puneeth2025-gnss-weather-api.hf.space/predict/demo-storm)

`Python` `TensorFlow` `Keras` `FastAPI` `Docker` `NumPy` `HuggingFace Spaces`

-----

<br/>

**AI-Powered Smart Home Security System**    `Final Year Major Project · VTU 2025-26`

A context-aware, multi-camera surveillance system that runs four AI models simultaneously on consumer hardware with complete local processing and zero cloud dependency.

> YOLOv8n + ByteTrack · InsightFace · MediaPipe Pose · Weapon Detection (YOLO)

- Achieved **76% reduction in false alarms** via session-based tracking — one alert per person per visit
- Face recognition at **88% accuracy** even at challenging 70° top-down camera angles, with a voting mechanism to prevent misclassifications
- Behavioral threat scoring with weighted multi-signal fusion: Pose (30%) + Movement (30%) + Temporal (20%) + Weapon (20%)
- Cross-camera identity linking that tracks a person’s journey from gate to door across separate feeds
- Sustains **15–18 FPS** with all four models running in parallel on a GTX 1650
- **My contribution:** Pose estimation & behavior analysis — MediaPipe 33-keypoint skeleton extraction, loitering/aggression detection, movement pattern analysis
- **Team:** Abhishek M · Adithya B Hanglur · Puneeth · Sarvan D Suvarna · Shamith Vakwady
- **Guide:** Mr. Balachandra R Jogi, Dept. of AI & DS, SMVITM

`Python` `PyTorch` `YOLOv8` `InsightFace` `MediaPipe` `ByteTrack` `OpenCV` `CUDA 11.8`

-----

**Digital Krishi Officer**

A multilingual AI advisory platform for Indian farmers combining a custom-trained disease classifier, a local knowledge base, and live data tools — all orchestrated by an LLM agent.

> MobileNetV2 · ChromaDB RAG · Groq (Llama 3.1) · WeatherAPI · AGMARKNET

- Custom-trained **MobileNetV2** on PlantVillage (70,000+ images) — classifies **38 disease classes** across 14 crop species
- Semantic search over local agricultural documents using **ChromaDB + Sentence Transformers**
- Live tool-calling for real-time weather forecasts and official AGMARKNET wholesale mandi prices
- Strictly enforced multilingual output in **English, Kannada, and Malayalam** regardless of input language
- Deployed on **Hugging Face Spaces** (backend) and **Vercel** (frontend)

`Python` `FastAPI` `PyTorch` `ChromaDB` `Next.js` `Groq API` `Docker`

-----

**FinVerse**

A production-grade fintech platform prototype designed to provide financial access to the unbanked through alternative credit scoring, peer lending, and AI-guided financial literacy.

> Next.js 14 · Supabase · Groq (Llama 3) · React Three Fiber · Framer Motion

- Proprietary **alternative credit scoring** algorithm (300–850) using non-traditional signals: rent history, utility payments, mobile usage patterns
- Real-time AI financial advisor powered by **Groq’s Llama 3** with persistent chat history in Supabase
- Full P2P lending marketplace with risk classification, borrower/lender flows, and RLS-secured data
- **React Three Fiber** 3D portfolio dashboard rendering live user financial data
- Complete authentication flow: signup, login, password reset, email verification via Supabase Auth
- Live at [finverse-prototype.netlify.app](https://finverse-prototype.netlify.app)

`Next.js 14` `TypeScript` `Supabase` `Groq` `React Three Fiber` `Tailwind CSS` `Framer Motion` `Recharts`

-----

**Sakhi Sahayak — Offline AI Village Assistant**

A fully offline Flutter application for rural and low-connectivity regions in India. The entire AI pipeline — speech recognition, intent detection, language model inference, and text-to-speech — runs on-device via native Android JNI with no internet required.

> Whisper Tiny Q8 · LLaMA 1B Q4 · Flutter · Kotlin · Android JNI

- On-device **Whisper Tiny Q8** for speech-to-text: PCM16 audio capture → Float32 conversion → JNI inference
- Quantized **LLaMA 1B Q4** simplifies complex task queries into 3–4 clear, actionable steps on-device
- Lightweight intent detector distinguishes Assist queries from incident Reports without a network call
- Pictogram-based visual guidance system designed for low-literacy users
- Zero cloud usage, zero external API calls — all audio processing on user action only
- Privacy-first architecture: no data ever leaves the device

`Flutter` `Kotlin` `Whisper` `LLaMA` `JNI` `Android` `Provider`

-----

**Land Use & Land Cover Change Detection (LULC)**    `Team Project`

A deep learning pipeline for semantic segmentation of satellite imagery and multi-year land-use change analysis, visualized through an interactive dashboard.

> U-Net · TensorFlow/Keras · Plotly Dash

- **U-Net** encoder-decoder with skip connections for pixel-wise multi-class segmentation: vegetation, water, urban, barren
- Cross-year change detection computing class-wise area deltas across regions and time periods
- Interactive **Plotly Dash** dashboard for exploring segmentation results and temporal trends
- Trained with combined Cross-Entropy + Dice loss, IoU metrics, and configurable augmentation
- **My contribution:** Data preprocessing pipeline, U-Net training, model integration, and all visualizations
- **Team:** Puneeth Hegde · Sarvan D Suvarna · Shamith Vakwadey · Abhishek M

`TensorFlow` `Keras` `NumPy` `OpenCV` `Plotly Dash` `Rasterio` `scikit-image`

-----

## Tech Stack

|Domain       |Technologies                                                                                                |
|-------------|------------------------------------------------------------------------------------------------------------|
|Languages    |Python · TypeScript · javascript · SQL                                                                            |
|AI / ML      |PyTorch · TensorFlow · YOLOv8 · InsightFace · MediaPipe · Whisper · LLaMA · ChromaDB · Sentence Transformers|
|Full-Stack   |Next.js · FastAPI · Flutter · Supabase · React Three Fiber · Tailwind CSS                                   |
|Tools & Infra|Git · Docker · CUDA · Vercel · Hugging Face Spaces · Linux                                                  |

-----

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=puneeth-hegde&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=e2e8f0&text_color=94a3b8&icon_color=6366f1&bg_color=0d1117" height="165"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=puneeth-hegde&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&title_color=e2e8f0&text_color=94a3b8&bg_color=0d1117" height="165"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=puneeth-hegde&theme=tokyonight&hide_border=true&background=0d1117&stroke=6366f1&ring=6366f1&fire=f59e0b&currStreakLabel=e2e8f0&sideLabels=94a3b8&dates=94a3b8" />

</div>

-----

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>

</div>
