# LLM Playground

A sleek, developer-focused LLM Playground web application inspired by the Groq Developer Console. Built with Vanilla JavaScript, Tailwind CSS, Marked.js, and Highlight.js in a single, high-performance, Vercel-ready architecture.

## Features

- **Multi-Provider Support:** First-class support for Groq (ultra-fast LPUs), xAI (Grok), OpenAI (GPT-4o), and OpenRouter.
- **Dynamic Prompt Analyzer:** Client-side heuristic engine that automatically detects Zero-Shot, One-Shot, and Few-Shot pattern structures with visual badge feedback.
- **Example Injector:** 1-click injection of structural few-shot templates (JSON extraction, classification, sentiment analysis).
- **Execution & Streaming:** Real-time streaming output (`TextDecoder` SSE parser) with pulsing cursor, live latency (ms), token generation speed (tok/s), and total token counters.
- **Parameter Controls:** Real-time temperature slider (`0.0 - 2.0`), max tokens slider (`1 - 8192`) with quick presets, Web Search Grounding toggle, and Top-P slider.
- **Dark & Light Mode:** Tailored developer console themes with smooth transitions.
- **Zero-Key Demo Mode:** Test and experience ultra-fast streaming responses without entering an API key.
- **API Model Diagnostics:** Automatic detection of key format, model permission verification, and dynamic model synchronization via `GET /models`.

## Deployment

Deployable instantly to Vercel or any static web host with zero build step.
