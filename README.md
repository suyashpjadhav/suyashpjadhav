<h1 align="center">
  Hi, I'm Suyash Jadhav
</h1>

<h3 align="center">
  Final-Year CSE Student at <b>BIT Mesra</b> |
  Backend & AI Agents Engineer |
  Gen AI & ML
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/suyashhj/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/suyashpjadhav">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:suyashjadhav1603@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.instagram.com/suyashhj/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
</p>

---

## Highlights

- **Software Engineer Intern (Backend & AI Agents) at Indunex AI**: built a DAG-based workflow engine and agentic automation for a manufacturing ERP
- **Research Intern (ML), BIT Mesra**: lifted a potato disease classifier from **69.94% to 86.06%** accuracy in the AgriAid project
- **IntervAI** is used by **100+ students** for AI-powered interview prep
- **500+ DSA problems** solved on LeetCode, GeeksforGeeks and Code360
- **Smart India Hackathon (SIH)** internal-round finalist, BIT Mesra
- Qualified **JEE Main and Advanced 2023**, with a top 3% category rank in JEE Main on the first attempt

---

## About Me

I build AI-powered products end to end, from the model and retrieval layer to the queues, APIs and databases that keep them reliable in production. I enjoy the point where LLMs meet solid backend engineering: async pipelines, caching, idempotency, schema validation and measurable evaluation.

- B.Tech in Computer Science and Engineering at **BIT Mesra** (2023 – 2027), CGPA **8.13/10**
- Currently a **Research Intern (ML)** in the Department of Computer Science, BIT Mesra
- Previously a **Software Engineer Intern (Backend & AI Agents)** at Indunex AI and a **Freelance AI Engineer** building a RAG course generator
- Day to day I work with AI coding tools (Google Antigravity IDE) for code generation, testing and debugging
- Ratnagiri, Maharashtra, India
- Open to collaborating on **multimodal intelligence systems** and **AI-native backend products**

---

## Experience

### Software Engineer Intern (Backend & AI Agents) | Indunex AI
`May 2026 – Jul 2026 · Remote`

**Workflow automation and AI agents for a manufacturing ERP.**

**Key Work:**
- Built a **DAG-based workflow execution engine** supporting 8+ node types, each with MongoDB-backed execution logic, passing context between nodes via topological sorting so every downstream AI agent receives the accumulated output of all upstream nodes
- Collaborated on an **agentic pipeline** that monitors 8+ workflow data sources, detects anomalies (overdue tasks, budget overruns, low stock) and triggers actions (emails, logs) autonomously
- Developed **Inngest** background functions for scheduled workflow triggers, BOM finalization, Google Form polling and inventory import, enabling durable, serverless job processing
- Built agent activity logging that stores tool calls, results, reasoning traces and run IDs in MongoDB for debugging and audit trails
- Implemented deadline monitoring in work-order nodes that detects overdue tasks and emails Clerk-authenticated assignees via Nodemailer/Resend
- Merged work-order state across MongoDB, Clerk metadata and node config using a defined priority hierarchy, and shipped a **WhatsApp-native interface** for field workers

**Tech Stack:** Node.js, MongoDB, Inngest, Clerk, graphology-dag, Nodemailer, Resend

---

### Research Intern, Machine Learning | BIT Mesra (Dept. of Computer Science)
`Jan 2026 – Present`

**AgriAid: a modular multimodal crop-advisory pipeline.**

**Key Work:**
- Engineered a pipeline that routes crop inputs through 2 independent branches (potato disease classification, rice disease severity) into one advisory output
- Fine-tuned an **EfficientNetB0** classifier for 7-class potato leaf disease detection, raising test accuracy from **69.94% to 86.06%** with two-phase training and Weights & Biases tuning
- Designed a 3-stage computer vision pipeline for rice Brown Spot severity: HSV leaf segmentation, **Segment Anything Model (SAM)** lesion detection and IRRI-standard grading, validated on 350 images
- Added a 3-tier confidence protocol (High / Moderate / Low) to flag uncertain predictions and reduce false-positive recommendations

**Tech Stack:** Python, PyTorch, EfficientNetB0, Segment Anything Model (SAM), HSV segmentation, Weights & Biases

---

### Freelance AI Engineer | RAG Course & Curriculum Generator
`Oct 2025 – Dec 2025 · Remote`

**A retrieval-grounded generator that builds courses from PDFs, slides and articles.**

**Key Work:**
- Integrated a **RAG pipeline (LangChain LCEL)** into an existing codebase, grounding courses in 3 source types (PDF, PPTX, articles) with a custom cosine-similarity chunker
- Replaced manual prompt engineering with a compiled **DSPy** pipeline (BootstrapFewShot) for rigid, hallucination-resistant output
- Built a 2-backend vector store (**ChromaDB** local, **Pinecone** cloud) with a SQLite hash/version manifest for idempotent indexing that skips unchanged documents
- Added cosine-similarity deduplication and token budgeting to size retrieved context by course duration

**Tech Stack:** Python, LangChain, DSPy, ChromaDB, Pinecone, Sentence-Transformers, NLTK, SQLite

---

## 🛠️ Tech Stack & Tools

### **Programming Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)

### **Generative AI & LLMs**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![DSPy](https://img.shields.io/badge/DSPy-4B0082?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F61?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FFB000?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)

### **ML & Computer Vision**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=for-the-badge)

### **Frontend Development**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=for-the-badge)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpinedotjs&logoColor=black)

### **Backend Development**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-E0234E?style=for-the-badge)
![Inngest](https://img.shields.io/badge/Inngest-000000?style=for-the-badge&logo=inngest&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### **Databases**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### **DevOps & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Antigravity](https://img.shields.io/badge/Google_Antigravity-4285F4?style=for-the-badge&logo=google&logoColor=white)

---

## Featured Projects

### [IntervAI: AI-Powered Interview Preparation Platform](https://github.com/suyashpjadhav/IntervAI)
**An LLM-powered platform used by 100+ students** that turns a resume into structured, schema-validated STAR interview prep sheets.

**Key Features:**
- Parses resumes with OpenAI `gpt-4o-mini` and generates STAR-format prep sheets, with 100% of outputs schema-validated (Zod, Mongoose)
- Asynchronous, queue-based report pipeline (BullMQ + Redis) that decouples LLM inference from HTTP requests, removing timeouts
- Automatic retry and backoff under API rate limits
- Redis caching to skip re-inference on repeated inputs
- Containerized with Docker

**Tech Stack:** React, Node.js, Express.js, MongoDB, OpenAI API, Redis, BullMQ, Zod, JWT, Docker

**Live Demo:** [intervai-app.vercel.app](https://intervai-app.vercel.app)

---

### [Mini Hiring Pipeline: Event-Sourced Tracker with NL Search](https://github.com/suyashpjadhav/mini-hiring-pipeline)
**An API-first, event-sourced candidate tracker** with a tamper-evident audit log and a deterministic natural-language search engine.

**Key Features:**
- SHA-256 hash-chained audit log, with pipeline integrity enforced by 5 SQL triggers, WAL-mode transactions and optimistic concurrency
- Deterministic natural-language search (rule parser, AST validator, SQL compiler, tiered fuzzy name matching) answering queries in **under 3 ms (p95 3.56 ms)**
- Offline evaluation harness over 47 queries: 100% route and exact-AST accuracy, 90.4% clause F1
- Quality gates (ruff, `mypy --strict`, 161 tests) enforced by a single check script

**Tech Stack:** Python, FastAPI, SQLAlchemy, SQLite, Alembic, HTMX, Alpine.js, uv

---

### [Mediversal: Healthcare Management Platform](https://github.com/rakshit432/Mediversal)
**A multi-role healthcare platform** for patients, doctors and admins.

**Key Features:**
- JWT-based role access control across patient, doctor and admin roles
- Conflict-free appointment booking
- HMAC-verified Razorpay payments
- Symptom triage bot powered by Gemini 2.5 Flash

**Tech Stack:** React 19, Express 5, MongoDB, Gemini API, Razorpay

**🔗 Live Demo:** [mediversal-tf2h.vercel.app](https://mediversal-tf2h.vercel.app)

---

### [Tire Safety Classifier](https://github.com/suyashpjadhav/Tire-Safety-Classifier)
**A ResNet-50 transfer-learning classifier** that labels tires as Safe or Defective with ~95% accuracy, deployed as a Gradio app.

**Tech Stack:** PyTorch, torchvision, Gradio, Hugging Face Spaces

**Live Demo:** [Hugging Face Space](https://huggingface.co/spaces/suyashpjadhav/Tire-Safety-Classifier)

---

### [SMS Spam Detector](https://github.com/suyashpjadhav/SMS-Spam-Detector)
**A PyTorch logistic-regression spam classifier** reaching 97.5% accuracy and 94% F1 on the UCI SMS Spam Collection.

**Tech Stack:** PyTorch, scikit-learn, Gradio, Hugging Face Spaces

**Live Demo:** [Hugging Face Space](https://huggingface.co/spaces/suyashpjadhav/SMS-Spam-Detector)

---

## How I Build

- **Async first:** long-running LLM work goes behind queues, with retries and backoff
- **Measure it:** evaluation harnesses and quality gates before I trust an output
- **Idempotent by design:** safe re-runs, hashes and manifests instead of repeated work
- **Validate everything:** schema-validated LLM output (Zod, Mongoose) over free-form text
- **AI-assisted, human-reviewed:** AI coding tools speed me up, and I review what ships

---

## Competitive Programming & Achievements

- **500+** Data Structures & Algorithms problems solved on LeetCode, GeeksforGeeks and Code360
- Smart India Hackathon (SIH) internal-round finalist, BIT Mesra
- Qualified JEE Main and Advanced 2023; top 3% category rank in JEE Main on the first attempt

---

## Currently Working On

- AgriAid crop-disease research at the CS Department, BIT Mesra
- Backend and AI systems: event sourcing, job queues, LLM pipelines and evaluation harnesses
- Looking for **SDE / Backend / Applied AI** internship opportunities for my 8th semester

---

## 📫 Let's Connect!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suyashhj/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/suyashpjadhav)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suyashjadhav1603@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/suyashhj/)

**Thanks for visiting! Feel free to reach out if you want to collaborate or just say hi!**

</div>
