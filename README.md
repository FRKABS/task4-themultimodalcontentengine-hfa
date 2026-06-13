# 🎬 HFA — AI Viral Content Engine

> **by Hafiz Farrukh Abbas**  
> Turn any video into 5 viral short-form Reels — powered by **Taimur AI (free)**, runs entirely in your browser.

[![Deploy to GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?logo=github)](https://pages.github.com)
[![Taimur AI](https://img.shields.io/badge/Powered%20by-Taimur%20AI%20(Free)-00cc88)](https://console.groq.com)
[![Author](https://img.shields.io/badge/Author-Hafiz%20Farrukh%20Abbas-e63f6b)](https://github.com/YOUR_USERNAME)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## 🚀 Live Demo

**[→ Open HFA AI](https://YOUR_USERNAME.github.io/hfa)**

---

## ✨ What It Does

HFA is a **fully browser-based** AI pipeline that:

1. 🎙️ **Transcribes** your video/audio using Taimur AI (LLaMA 3.3 70B)
2. 🧠 **Scores** every segment for viral potential (hook, emotion, shareability, novelty)
3. ✍️ **Generates** captions, hooks, headlines & CTAs per platform
4. 🎬 **Creates** Runway Gen-3 B-roll prompts ready for AI video generation
5. 📦 **Exports** everything as JSON or copy-pastes to clipboard

---

## 🔑 Get Your FREE Groq API Key (2 minutes)

1. Go to **[console.groq.com](https://console.groq.com)**
2. Click **Sign Up** — free, no credit card needed
3. Go to **API Keys** → **Create API Key**
4. Copy your key
5. Paste it into HFA when prompted — saved only in your browser tab

**Groq free tier limits:** 14,400 requests/day · 500,000 tokens/min · completely free

---

## 🔌 Requirements

- A modern browser (Chrome, Firefox, Safari, Edge)
- A free Groq API key (see above)
- Your video or audio file (MP4, MOV, AVI, MKV, MP3, WAV, M4A, WEBM)

---

## 🚢 Deploy to GitHub Pages (2 minutes)

1. Fork or clone this repo
2. Go to **Settings → Pages → Source: GitHub Actions**
3. Push to `main` — auto-deploys in ~60 seconds
4. Visit `https://YOUR_USERNAME.github.io/hfa`

---

## 📁 Project Structure

```
hfa/
├── index.html                   ← Entire web app (single file, no build step)
├── README.md
├── .github/
│   └── workflows/
│       └── deploy.yml           ← GitHub Actions auto-deploy
└── src/                         ← Optional Python CLI pipeline
    ├── pipeline.py
    ├── transcriber.py
    └── ...
```

---

## 🔒 Privacy & Security

- Your Groq API key is saved **only in your browser tab** (sessionStorage — clears on tab close)
- Video files are **never uploaded** to any server
- Only the transcript text is sent to Taimur AI for analysis
- No accounts, no tracking, no backend

---

## 🧠 How the AI Pipeline Works

```
VIDEO/AUDIO FILE (browser)
        │
        ▼
┌─────────────────────────────┐
│  Taimur AI — Transcribe     │  → Timestamped segments
│  LLaMA 3.3 70B (free)       │
└─────────────────────────────┘
        │
        ▼
┌─────────────────────────────┐
│  Taimur AI — Viral Scoring  │  → 0-100 score per segment
│  5 criteria × 20 pts each   │
└─────────────────────────────┘
        │
        ▼
┌─────────────────────────────┐
│  Taimur AI — Captions       │  → Headline, hook, caption,
│                             │     CTA, hashtags, A/B test
└─────────────────────────────┘
        │
        ▼
┌─────────────────────────────┐
│  Taimur AI — B-Roll         │  → Runway Gen-3 prompts
└─────────────────────────────┘
        │
        ▼
    📋 Copy / ⬇ Download JSON
```

---

## 📄 License

MIT © 2026 **Hafiz Farrukh Abbas**
