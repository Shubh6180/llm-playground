# LLM Playground

[![Live Demo](https://img.shields.io/badge/Live_Demo-Vercel-black?style=for-the-badge&logo=vercel)](https://grok-ten-azure.vercel.app)
[![GitHub License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)](LICENSE)

> A sleek, developer-focused LLM Playground web application inspired by the Groq Developer Console. Built with Vanilla JavaScript, Tailwind CSS, Marked.js, and Highlight.js in a single, high-performance, Vercel-ready architecture.

---

### 🌐 Live Application

**Experience the playground live on Vercel:**  
👉 **[https://grok-ten-azure.vercel.app](https://grok-ten-azure.vercel.app)**

*(Includes **Demo Mode** — you can test the playground with simulated ultra-fast responses without needing an API key!)*

---

## ✨ Features

- **Multi-Provider Support:** First-class support for Groq (ultra-fast LPUs), xAI (Grok), OpenAI (GPT-4o), and OpenRouter.
- **Dynamic Prompt Analyzer:** Client-side heuristic engine that automatically detects Zero-Shot, One-Shot, and Few-Shot pattern structures with visual badge feedback.
- **Example Injector:** 1-click injection of structural few-shot templates (JSON extraction, classification, sentiment analysis).
- **Execution & Streaming:** Real-time streaming output (`TextDecoder` SSE parser) with pulsing cursor, live latency (ms), token generation speed (tok/s), and total token counters.
- **Parameter Controls:** Real-time temperature slider (`0.0 - 2.0`), max tokens slider (`1 - 8192`) with quick presets, Web Search Grounding toggle, and Top-P slider.
- **Dark & Light Mode:** Tailored developer console themes with smooth transitions.
- **Zero-Key Demo Mode:** Test and experience ultra-fast streaming responses without entering an API key.
- **API Model Diagnostics:** Automatic detection of key format, model permission verification, and dynamic model synchronization via `GET /models`.

---

## 🚀 Deployment

The project is hosted and continuously deployed on Vercel:

- **Production URL:** [https://grok-ten-azure.vercel.app](https://grok-ten-azure.vercel.app)
- **Deployment URL:** [https://grok-e8nfdiaha-4pi.vercel.app](https://grok-e8nfdiaha-4pi.vercel.app)
- **Repository:** [https://github.com/Shubh6180/llm-playground](https://github.com/Shubh6180/llm-playground)

---

## 💻 Local Usage

Simply clone the repository and open `index.html` directly in your browser:

```bash
git clone https://github.com/Shubh6180/llm-playground.git
cd llm-playground
open index.html
```
No build steps, node modules, or bundlers required.
