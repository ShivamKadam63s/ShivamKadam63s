# Hey, I'm Shivam 👋

Third-year Computer Engineering student at **SPIT Mumbai** (CGPA 9.77) with a Management minor at **SPJMR**. I build things at the intersection of systems programming, infrastructure, and generative AI — usually because something I was using frustrated me enough to replace it.

I'm drawn to understanding how things work underneath, not just how to use them. Using a library is never enough — I want to know what the library is doing, and why it made the tradeoffs it did. That instinct shows up in everything I build.

## 🛠️ What I'm Working With

**Languages**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Frameworks & Tools**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tauri](https://img.shields.io/badge/Tauri-FFC131?style=flat&logo=tauri&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)



## 🚀 Projects

### [WebLaunch](https://github.com/ShivamKadam63s/WebLaunch) — Self-Hosted PaaS
`Node.js` `Kubernetes` `Docker` `Bull/Redis` `Prometheus` `Grafana` `Terraform` `Ansible`

Paste a GitHub URL. WebLaunch detects the stack, writes a Dockerfile, builds the image, deploys it to Kubernetes, and starts monitoring it — zero configuration required. Supports 18 tech stacks including React, Next.js, Django, Go, Rust, and Spring Boot. Full observability stack with pre-wired Grafana dashboards and 4 alert rules out of the box.



### [GitLane](https://github.com/ShivamKadam63s/GitLane) — Desktop Git Client
`Rust` `Tauri 2` `React` `TypeScript` `libgit2` `Docker`

An offline-first desktop Git client that talks directly to libgit2 — no system Git required, no Electron overhead. Runs at ~10 MB vs the ~150 MB of Electron-based alternatives. Full Git workflow: commits, branching, visual diffs, stash, three-way merge, HTTPS remote sync with credential storage. Includes P2P repository transfer over local network via QR code handshake and mDNS discovery — no internet needed.



### [Mythological SLM](https://www.kaggle.com/code/shivamkadam63/mythological-domain-slm) — Transformer Trained from Scratch
`PyTorch` `tiktoken` `AMP` `Python`

GPT-style decoder-only transformer (50M parameters, 8 layers, 8 heads, 512-dim) trained from random initialisation on ~30M tokens from 22 Project Gutenberg mythological texts — Mahabharata, Ramayana, Vishnu Purana, Iliad, Odyssey, and others. Custom corpus cleaning pipeline, AdamW with cosine decay, float16 AMP, gradient accumulation. Evaluated across 20 structured domain prompts with top-k sampling and repetition penalty.



### [BERTopic Agentic Pipeline](https://huggingface.co/spaces/spjimr-bertopic/bertopic-agent-final) — LLM-Powered Topic Modelling
`LangGraph` `BERTopic` `Mistral` `Groq Llama-3` `Gradio` `Plotly`

LangGraph-driven pipeline implementing Braun & Clarke's 6-phase thematic analysis on academic paper abstracts. Features an "AI Council" where Mistral-Large and Groq Llama-3 independently label each cluster and debate to a consensus, with a per-topic consensus score for auditability. Maps outputs to a 25-category PAJAIS taxonomy with novelty scoring. Deployed live on Hugging Face Spaces.


## 💼 Experience

**Software Engineering Intern @ [Snipto App](https://snipto.critso.com/) — CRITSO, Mumbai** *(Jul–Aug 2025)*

Built the core backend in Rust for a cross-platform (Windows/macOS/Linux) Tauri desktop app — OS-level keystroke detection, clipboard simulation, shortcut validation, global hotkey profile switching in a background thread, and a full JSON import/export pipeline across the Rust–React IPC bridge.

## 📬 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shivam%20Kadam-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shivam-kadam-136601354/)
[![Email](https://img.shields.io/badge/Email-shivam.kadam23@spit.ac.in-D14836?style=flat&logo=gmail&logoColor=white)](mailto:shivam.kadam23@spit.ac.in)
[![Kaggle](https://img.shields.io/badge/Kaggle-shivamkadam63-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/shivamkadam63)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-spjimr--bertopic-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/spjimr-bertopic/bertopic-agent-final)
