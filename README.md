# 🌟 Senior Software Architect|Liferay Architect | AI Engineer|Computer Vision & AI Enterprise Engineering  | RAG | Agentic AI | LLMOps 

> **Senior Software Engineer (26+ yrs)** | **AI ,Agents & Computer Vision Specialist** | **Enterprise Java & Liferay Architect**  
> Building **AI-powered systems**, **forensic-grade detection platforms**, and **enterprise-scale applications**
> My current focus is on **RAG, LLM engineering, Agentic AI, AI security, LLMOps and enterprise AI integration**
> **AI integrations in Liferay  platforms** — combining modern AI capabilities with the engineering discipline required for secure, reliable business applications.

---

## 🧭 Quick Overview 

- 🧠 **AI & Computer Vision** — Image forensics, GAN & diffusion detection, OpenCV, PyTorch  
- 🕵️ **Forensic Systems** — Court-ready reporting, chain of custody, evidence workflows  
- 🤖 **AI Agents & Chatbots** — LLMs, Flowise, voice-enabled assistants  
- 🏢 **Enterprise Engineering** — Java, Spring, Liferay, Docker, Elasticsearch  
- 🚀 **Production-first mindset** — Scalable, secure, Dockerized systems  

---

## 🏷️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![Liferay](https://img.shields.io/badge/Liferay-7.4-purple)
![AI](https://img.shields.io/badge/AI-LLM%20%7C%20Agents-orange)
![Forensics](https://img.shields.io/badge/Digital-Forensics-black)

---
## 🧠 Featured Project — EWS CareAgent — Secure RAG & Agentic AI

**CareAgent** is a production-shaped AI engineering reference platform I architected and developed to demonstrate how **RAG, LLMs and Agentic AI** can be engineered for secure enterprise applications.

> **Core principle:** The model can reason and propose. The application owns authorization, approval and execution.

### 🚀 Engineering Highlights

* 🔎 **Permission-Aware RAG** — hybrid lexical + vector retrieval, pgvector, RRF, reranking, citations and abstention
* 🤖 **Agentic AI** — bounded workflows, state/memory, tool selection and closed tool registry
* 👤 **Controlled Actions** — human approval, ownership validation, TTL, reauthorization, idempotency and audit
* 🛡️ **AI Security** — ACL-before-context, prompt-injection protection, structured validation and multi-layer guardrails
* 📊 **AI Evaluation** — Hit@K, Precision, Recall, MRR, nDCG, adversarial and regression testing
* 🦙 **LLMOps & Local AI** — provider abstraction, Ollama/Llama, fallback, telemetry and model/prompt lifecycle
* 🔐 **Privacy by Design** — **Allowed? → Needed? → Must it leave?**

### 🏗️ Architecture


<p align="center">
  <img src="CareAgent — Secure RAG & Agentic AI Architecture.png" alt="CareAgent — Secure RAG & Agentic AI Architecture" width="850">
</p>

### ⚙️ Core Stack

`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `Redis` · `React` · `TypeScript` · `Docker` · `Ollama` · `pytest` · `Playwright`

### 💡 What CareAgent Demonstrates

CareAgent is **not just an AI chatbot**. It combines retrieval, reasoning and controlled actions with conventional application security and measurable evaluation.

**RAG Quality + Agentic AI + AI Security + Human Control + LLMOps**

The goal is simple: build AI systems that can do useful work **without making the LLM the application's security or authorization boundary**.


## 🌿  My Healthy Living

A production-ready **personal healthy-living companion** that combines practical meal planning, recipe management, shopping, pantry tracking, progress check-ins, and configurable email routines in one mobile-friendly web application.

The platform blends **Mediterranean food principles** with carefully curated **Ayurvedic food knowledge**, while keeping traditional guidance, modern nutrition, recipe verification, and personal experience clearly separated.

🔗 **Live Demo:** https://my-healthy-living-guide.vercel.app

<p align="center">
  <img src="my-healthy-living-dashboard.png" alt="My Healthy Living Dashboard" width="850">
</p>

<details open>
<summary><strong>✨ What the Application Delivers</strong></summary>

- 🌞 **Personalized Today Dashboard** — Daily meals, focus, prep tasks, shopping preview, and progress
- 📅 **Adaptive Weekly Planner** — Deterministic meal planning with exclusions, preferences, locks, replacements, and explainable recommendations
- 🍲 **Recipe Library** — Curated recipes, favorites, My Recipes, personal versions, cooking notes, and history
- 🛒 **Smart Shopping Workflow** — Consolidated ingredient identity, pantry subtraction, store/category grouping, print/PDF/copy/share
- 🧺 **Pantry Management** — Have / Low / Out status with quantity-aware shopping integration
- 📈 **Progress Tracking** — Lightweight daily check-ins with weekly and monthly views
- 🔎 **Discover** — Recipes, ingredients, knowledge, and optional external recipe discovery
- 🌿 **Ingredient Library** — Multilingual ingredients, where-to-buy information, pantry/shopping actions, and trusted image fallbacks
- 📧 **Daily / Weekly Email Companion** — Timezone-aware scheduled routines with branded HTML emails and recipient-specific privacy
- 👥 **Private Multi-user Access** — Supabase magic-link authentication, owner/demo roles, household isolation, and RLS
- 📱 **PWA / Mobile-first UX** — Responsive design, installable application, mobile shopping mode, and safe offline fallback

</details>

<details>
<summary><strong>🧠 Knowledge & Trust Architecture</strong></summary>

The system separates knowledge by source and confidence rather than mixing everything into generic wellness advice.

- Classical Ayurveda references
- Institutional Ayurveda sources
- Mediterranean dietary guidance
- Modern nutrition sources
- Food-safety sources
- Source tiers and provenance
- Human-review workflow
- Traditional vs modern knowledge labels
- No automatic medical or dosha diagnosis
- No unreviewed knowledge used by the meal planner

</details>

<details>
<summary><strong>🍽️ Recipe & Personalization Model</strong></summary>

Three distinct recipe layers are maintained:

1. **Curated Recipes** — protected editorial recipes
2. **My Recipes** — user-created personal recipes
3. **My Version** — personal adaptations of curated recipes

Cooking experience can include:

- ratings
- quick feedback tags
- cooking notes
- cooking history
- favorites
- personal versions

The original curated recipe always remains protected.

</details>

<details>
<summary><strong>⚙️ Planning & Shopping Engine</strong></summary>

The meal planner follows a deterministic pipeline:

`hard filters → preferences → soft scoring → ranking → controlled relaxation → plan`

Important safeguards include:

- excluded foods are never relaxed
- rejected recipes never enter plans
- seeded deterministic selection
- variety and recent-recipe penalties
- pantry and expiry awareness
- family / schedule / light-dinner signals
- locked meals survive regeneration
- reason codes explain recommendations

Shopping reuses canonical ingredient identity rather than fuzzy matching and safely preserves incompatible units instead of inventing conversions.

</details>

<details>
<summary><strong>📧 Notification System</strong></summary>

- Daily Companion
- Weekly Planner
- Monthly Review
- Prep / Shopping / Meal reminders
- Multiple recipients
- Per-recipient preferences
- Europe/Athens and IANA timezone support
- Hourly Vercel cron evaluation
- Resend verified sender
- Delivery audit + occurrence-key idempotency
- Personal progress kept private from household recipients
- App users and notification recipients remain separate concepts

</details>

<details>
<summary><strong>🔐 Architecture & Security</strong></summary>

- Next.js / React
- Supabase Auth with magic links
- PostgreSQL / Supabase
- Row Level Security
- Household + personal data ownership
- Vercel deployment
- Resend email delivery
- PWA / offline fallback
- Server-only service-role and email credentials
- Private/demo access model
- Protected editorial Studio
- Canonical content separated from personal content

</details>

<details>
<summary><strong>🛠️ Tech Stack</strong></summary>

- Next.js
- React / TypeScript
- Tailwind CSS
- Supabase / PostgreSQL
- Vercel
- Resend
- PWA / Service Worker
- Lucide React
- Deterministic TypeScript planning engine

</details>

<details>
<summary><strong>✅ Current Status</strong></summary>

- Production deployment complete
- Mobile-first UI complete
- Recipe / ingredient / shopping quality audits in place
- Cloud plans, pantry, shopping, progress and personal content supported
- Multi-recipient notification architecture complete
- Private demo-user testing underway
- Further development intentionally paused while real-user feedback is collected

</details>

---

🤖  **Digital Twin AI Chatbot (Voice Enabled)**

An **enterprise-grade AI-powered digital twin** built with LLMs that maintains context, understands intent, and qualifies leads through natural conversations.

🔗 **Live Demo:** https://my-twin-bot.vercel.app/

<p align="center">
  <img src="vaibhav-twin-bot.png" alt="Vaibhav Twin Bot" width="600" >
</p>

<details open>
<summary><strong>🎤 Voice Features — Interactive AI Assistant</strong></summary>

- **🎙️ Voice Input** — Click the mic and speak naturally  
- **🔊 Voice Output** — Hear responses in natural speech  
- **🔀 Hybrid Mode** — Text + voice simultaneously  
- **👤 Voice Customization** — Male / Female voice  
- **🔒 Privacy First** — All voice processing in your browser (no audio upload)  
- **⚡ Zero Latency** — Instant recognition + speech synthesis  
- **📱 Mobile Ready** — Works on Chrome for Android  

</details>

<details>
<summary><strong>🎯 How to Use</strong></summary>

1. Open: https://my-twin-bot.vercel.app/  
2. Click **Settings** (⚙️)  
3. Choose input/output modes + voice gender  
4. Click the **microphone** and start speaking  

</details>

<details>
<summary><strong>🔐 Privacy & Security</strong></summary>

- ✅ No audio upload  
- ✅ No storage of voice recordings  
- ✅ Microphone permission only with consent  
- ✅ Conversations stay between you and your browser  

</details>

---

## 🕵️‍♂️ Featured Project — Forensic Image & AI-Detection System

A **full-stack forensic web application** designed to detect **AI-generated, manipulated, and authentic images** with **end-to-end case management** and **court-ready reporting**.

<p align="center">
  <img src="forentic-app-details-1.png" alt="Forensic AI Detection Architecture" width="500" >
</p>

<details open>
<summary><strong>🚀 What the System Delivers</strong></summary>

- 🧩 End-to-end forensic case tracking  
- 👥 Role-based access (Admin / Analyst / User) + audit-ready chain of custody  
- 🔬 Deep forensic analysis (EXIF, ELA, FFT, noise patterns, JPEG artifacts, similarity metrics)  
- 📄 Professional **PDF + JSON** reports (hashes, signatures, structured forensic narratives)  
- ⚙️ Background processing for large images + Dockerized deployment  

</details>

<details>
<summary><strong>🧠 Core Detection & Forensic Modules</strong></summary>

- EXIF metadata extraction & validation  
- Error Level Analysis (ELA)  
- FFT frequency-domain analysis  
- Noise residual mapping  
- JPEG blockiness detection  
- Face vs background consistency  
- Image comparison: ORB alignment, SSIM, PSNR  
- AI generation detection: GAN / Diffusion / Real classifiers (format-aware logic)  

</details>

<details>
<summary><strong>🖼️ Supported Image Categories</strong></summary>

- AI-generated: GANs, Stable Diffusion, DALL·E, Midjourney  
- Authentic photos: special focus on **pre-2011 digital camera images**  

</details>

<details>
<summary><strong>🧪 Detection Strategy</strong></summary>

- GAN artifact detection  
- Diffusion model detection  
- Authenticity verification (camera signatures + sensor characteristics)  

</details>

<details>
<summary><strong>📚 Research Foundation</strong></summary>

- Wang et al. (2020) — CNN-generated images  
- Corvi et al. (2023) — Diffusion model detection  
- Lukas et al. (2006) — Digital camera identification via sensor pattern noise  

</details>

<details>
<summary><strong>✅ Current Status</strong></summary>

- Core features implemented end-to-end  
- Professional, court-ready reports generated  
- Workflow supports real forensic / evidence use cases  

</details>

---

## 🧠 AI Agents & Enterprise Chat Systems

<details open>
<summary><strong>🤖 Intelligent Chat Portlet for Liferay (AI-Powered CMS)</strong></summary>

Turn complex content operations into simple conversations.


<table>
  <tr>
    <td align="center">
     <img src="liferay-agent-chat.png" alt="Liferay Agent Chat" width="420">
      <br/>
      <sub><b>Liferay Agent Chat</b></sub>
    </td>
    <td align="center">
      <img src="Intelligent-chat-artchitecture.png" alt="Intelligent Chat Architecture" width="420">
      <br/>
      <sub><b>Intelligent Chat Architecture</b></sub>
    </td>
  </tr>
</table>

<details>
<summary><strong>🎯 Examples</strong></summary>

- “Create blog titled 'Docker Guide' about containerization” → ✅ Blog created instantly  
- “List all web content” → 📋 Formatted table with IDs, titles, dates  
- “Update article 34180 with new pricing” → ✔️ Updated and confirmed  
- “How to create a custom portlet?” → 📚 Answered from documentation  

</details>
<details>
<summary><strong>🎯 **Innovation**</strong></summary>

- Intelligent query routing to the right backend:
  - txtai for semantic documentation search  
  - Ollama (LLM) for general knowledge  
  - Liferay Headless API for content operations  
  - NLP for intent detection   

</details>

<details>
<summary><strong>🎯 **Tech Stack**</strong></summary>

- Liferay Portal 7.4+ (Java/OSGi)  
- txtai (semantic search)  
- Ollama (llama3.2:1b)  
- Elasticsearch 7.17  
- Docker & Docker Compose  

</details>

---

## 👁️ Computer Vision Projects (with Proof Images)

<details open>
<summary><strong>📂 Project Index (Click to Expand)</strong></summary>

### 1) [Automatic Number Plate Recognition (ANPR) for Electronic Toll Collection](https://github.com/lalitavai/AutomaticNumberPlateRecognition)
![ANPR](NPL-detection.png)

### 2) [Train an Image Classifier From Scratch](https://github.com/lalitavai/ImageClassifierFromScratch)
![Training Scratch](training-scratch.png)  
![Training Model](training-model-cratch.png)

### 3) [Image Instagram Filters](https://github.com/lalitavai/imageInstgramFilters)
![Instagram Filters](instgram-filters.png)

### 4) [Document Scanner](https://github.com/lalitavai/documentScanner)
![Document Scanner](doucmenr-scanner-project.png)

### 5) [AI Chatbots for KNC Product Catalogue & Sahaja Yoga (Flowise Agents)](https://github.com/lalitavai/ai-agents)
![KNC Flowise](knc-flowise.png)  
![Sahaja Yoga Bot](ShriMatajiOrg-chat.png)

### 6) [Blemish Removal](https://github.com/lalitavai/blemishRemoval)
![Blemish Removal](blemish-project.png)

### 7) [Green Screen Effect](https://github.com/lalitavai/greenScreenEffect)
![Green Screen](greenscreeneffect.png)

### 8) [Image Cropping Tool](https://github.com/lalitavai/imageCroppingTool)
![Cropping Tool](imageCropping.png)

### 9) [Coin Detection and Analysis](https://github.com/lalitavai/coinDetectionAnalysis)
![Coin Detection](coin-detections.png)

### 10) [Video Frame Sharpness Analyze](https://github.com/lalitavai/videoFrameSharpness)
![Video Sharpness](autofocus-video-lapacian.png)

### 11) [Panoramic Image Stitching](https://github.com/lalitavai/panoramaImageStitching)
![Stitched Panorama](stiched-image.png)

### 12) [Data Understanding & Pipeline Check](https://github.com/lalitavai/DataunderstandingAndPiplelineCheck)
![Data Understanding](data-understanding-classifications.png)

</details>

---

## 🛠️ Technologies Used

<details open>
<summary><strong>Click to View</strong></summary>

- Python 3.x, OpenCV, NumPy, Pandas, Matplotlib  
- PyTorch  
- Flowise (AI Agents)  
- Ollama (embeddings / LLM runtime)  
- Docker  
- Node.js  
- Other image processing libraries  

</details>

---

## 🧠 Models Used

- CNNs  
- Segmentation: U-Net, ResNet50  
- Object Detection: YOLO, Detectron2  

---

## 🚀 How to Get Started

1. Click any project link above to explore its repository  
2. Follow the repo instructions to run or contribute  

---

## 📫 Contact

- **Email:** [lalitavai@hotmail.com](mailto:lalitavai@hotmail.com)  
- **GitHub:** https://github.com/lalitavai  

⭐ Thanks for visiting!
