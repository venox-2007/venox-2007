<div align="center">

<img src="https://raw.githubusercontent.com/venox-2007/venox-2007/main/assets/venox-wordmark-banner.png" width="100%" alt="venox — build, experiment, ship — purple circuit design" />

# Hi, I'm Yug 👋
### AI experiments. Local tools. Useful interfaces.

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=1100&color=38BDF8&center=true&vCenter=true&width=700&height=55&lines=Building+models+from+the+ground+up;Exploring+speech%2C+documents+%26+local+AI;From+experiment+to+interface" width="700" alt="Building models from the ground up · Exploring speech, documents and local AI · From experiment to interface" />

I build across the stack: model internals in PyTorch, Python APIs, and React interfaces.<br>
My repositories explore small language models, speech processing, document extraction, and local AI assistants.

[Explore projects](#-selected-projects) · [Browse repositories](https://github.com/venox-2007?tab=repositories) · [GitHub activity](https://github.com/venox-2007?tab=overview)

</div>

---

## 🔬 What I build

- **Models from first principles** — tokenization, causal attention, training loops, and text generation.
- **Experiments with evidence** — comparing extraction tools and measuring audio quality alongside recognition errors.
- **AI tools with interfaces** — local model integration, permission-aware workflows, and web or desktop frontends.

## 🧰 Technologies used in my projects

These badges reflect repository code and tooling, rather than a claim of expertise in every technology.

**Languages & web fundamentals**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-B89B00?style=for-the-badge&logo=javascript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)

**Models, retrieval & data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-4DABCF?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-222222?style=for-the-badge&logo=ollama&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-2563EB?style=for-the-badge)

**Applications & testing**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-087EA4?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-087EA4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=for-the-badge&logo=electron&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

## ✨ Selected projects

### 🧠 [GroundUpGPT](https://github.com/venox-2007/GroundUpGPT)
**A small GPT-style language model, built from the fundamentals.**

Custom byte-level BPE, causal self-attention, decoder blocks, pretraining and conversational fine-tuning code, plus a FastAPI streaming backend and Next.js chat interface. The repository documents experiments with approximately 5M and 27M parameter models.

`Python` `PyTorch` `FastAPI` `Next.js`  
**Scope:** Educational model engineering; trained checkpoints are local artifacts and are not bundled in the repository.

### 🌾 [FarmWise](https://github.com/venox-2007/FarmWise)
**A multilingual agriculture assistant with crop-image analysis and live voice/video interaction.**

Combines Gemini-powered crop analysis, structured treatment suggestions, a live assistant that accepts camera frames and microphone audio, and Open-Meteo weather forecasts. A React/TypeScript interface brings together crop advice, market views, and agricultural schemes.

`TypeScript` `React` `Gemini API` `Vite`  
**Scope:** API-integrated application prototype; market prices come from local data, and farmer login is a local profile flow.

### 🎙️ [Speech Enhancement & ASR Correction](https://github.com/venox-2007/speech-enhancement-asr-correction)
**A trained U-Net, pretrained Whisper, and pronunciation-aware transcript correction.**

Includes a Streamlit demo, a committed enhancement checkpoint, and saved evaluations on 824 test recordings. The key finding: denoising improves objective audio metrics but increases Whisper word errors; conservative correction yields a small improvement within each audio path.

`Python` `PyTorch` `Whisper` `GPT-2` `Streamlit`  
**Scope:** Completed experiment with documented limitations; the full pipeline does not beat Whisper on the original noisy audio.

### 📄 [PDF Extraction Benchmark](https://github.com/venox-2007/pdf-extraction-benchmark)
**Comparing document extraction approaches through a shared evaluation toolkit.**

Adapters for PyMuPDF, OpenDataLoader, PaddleOCR, Tesseract, and Docling, with native/scanned document classification, benchmark pipelines, reports, and a Streamlit comparison interface.

`Python` `OCR` `PyMuPDF` `Streamlit`  
**Scope:** Implemented benchmarking toolkit; results depend on document type, dataset, and runtime environment.

### 🖥️ [Personal AI OS](https://github.com/venox-2007/personal-ai-os)
**A local AI assistant project with a desktop interface.**

Combines an Ollama tool-calling provider, FastAPI backend, memory and workflow modules, permission and approval handling, and a React/Electron frontend. Includes backend tests and desktop packaging scripts.

`Python` `Ollama` `FastAPI` `React` `Electron`  
**Scope:** Development project; integrations and packaging need to be evaluated in their intended local environment.

### 📋 [Akshar Connect](https://github.com/venox-2007/akshar-connect-attendance-app)
**Attendance and student-record workflows for an educational NGO use case.**

Teacher/admin views, attendance history, CSV exports, and English/Hindi/Marathi interfaces. The code includes Supabase authentication/data paths, a PostgreSQL migration with access policies, and a local demo fallback.

`TypeScript` `React` `Tailwind CSS` `Supabase`  
**Scope:** Demo plus backend integration code; live deployment and server-side policy enforcement are not established by the repository alone.

<details>
<summary><b>🌱 More builds & earlier experiments</b></summary>

<br>

| Project | What it explores |
| :--- | :--- |
| [ResearchOS](https://github.com/venox-2007/research-os) | Research-workflow prototype with FAISS/BM25 retrieval, LangGraph orchestration, and traceable evidence; the current LLM factory uses mock providers. |
| [AtomQuest Goal Portal](https://github.com/venox-2007/atomquest-goal-portal) | React hackathon dashboard for goal approvals, weight validation, quarterly check-ins, and reports using mock data. |
| [TaskMaster](https://github.com/venox-2007/TaskMaster-Vibe2Ship) | React/Express productivity-coach prototype with Gemini-backed planning and a focus timer. |
| [Global Population Predictor](https://github.com/venox-2007/global-population-predictor) | Streamlit exploration of country population trends using quadratic regression; forecasts are illustrative extrapolations. |
| [Merit & Mint](https://github.com/venox-2007/Merit-Mint) | Static skincare storefront demo with product filters and quick views; contact submission is frontend-only. |

</details>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=venox-2007&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=C4A7E7&amp;icon_color=A78BFA&amp;text_color=C9D1D9" width="495" alt="venox-2007 GitHub statistics" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=venox-2007&amp;theme=tokyonight&amp;hide_border=true&amp;background=0D1117&amp;ring=A78BFA&amp;fire=C4A7E7&amp;currStreakLabel=C4A7E7" width="495" alt="venox-2007 contribution streak" />
</p>

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=venox-2007&amp;layout=compact&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=C4A7E7&amp;text_color=C9D1D9" width="495" alt="Most used languages across public repositories" />
</p>

<p align="center">
  <sub>Cards refresh periodically. Language percentages reflect repository code, not proficiency.</sub>
</p>

---

<div align="center">

**From model internals to the interface around them.**

[Code & repositories](https://github.com/venox-2007?tab=repositories) · [Contributions & activity](https://github.com/venox-2007?tab=overview)

</div>
