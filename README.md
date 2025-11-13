# Multimodal Controller

A Python-based multimodal control system that allows users to control applications using **voice commands** and **hand gestures**.  
This project integrates speech recognition, gesture detection, command mapping, and action execution into one modular system.

---

## 🧭 Project Summary

The Multimodal Controller is designed to combine **voice inputs** and **gesture inputs** to control desktop tasks such as opening applications, navigating screens, controlling media, scrolling, and more.

This project is developed as part of a structured weekly learning plan:
- Week 0 → Setup and planning  
- Week 1 → Voice recognition  
- Week 2 → Gesture detection  
- Week 3 → Intent mapping  
- Week 4 → Action execution + MVP  

---

## 🎯 Goals

1. Build a **working prototype (MVP)** where voice and gestures control basic apps.
2. Create a clean **command taxonomy** (30–40 voice commands + gestures).
3. Develop a modular architecture:
   - Input Adapters (voice + gesture)
   - Intent Mapper
   - Command Dispatcher
   - Action Executor
4. Write readable and maintainable Python code.
5. Use GitHub branches for clean workflow (main, dev, mvp).
6. Create proper documentation and issue tracking.

---

## 📂 Branch Strategy

- **main** — fully stable, tested code  
- **dev** — active development work  
- **mvp** — assembling first working version  

All new features should go into `dev`.

---

## 🚀 Installation

```bash
git clone https://github.com/<your-username>/multimodal-controller
cd multimodal-controller

python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

pip install -r requirements.txt
