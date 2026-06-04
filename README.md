<!--
description: A collaborative and community-maintained list of publicly available AI APIs for developers, researchers, and enthusiasts, covering LLMs, image generation, speech, vision, and more.
keywords: AI APIs, machine learning APIs, artificial intelligence, LLM APIs, image generation APIs, speech APIs, vision APIs, open-source AI, free AI APIs, developer tools, AI integrations, awesome list
-->
# Awesome AI APIs 🚀

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/awesome-ai-apis?style=social)](https://github.com/ishandutta2007/awesome-ai-apis/stars/0) [![GitHub contributors](https://img.shields.io/github/contributors/ishandutta2007/awesome-ai-apis)](https://github.com/ishandutta2007/awesome-ai-apis/graphs/contributors) [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A collaborative list of **publicly available AI APIs** for developers, researchers, and enthusiasts. Manually curated and maintained by the community. Inspired by [public-apis/public-apis](https://github.com/public-apis/public-apis).

This directory focuses exclusively on **AI/ML APIs** including LLMs, image generation, speech, vision, agents, and more. We prioritize free tiers, open-source models, and production-ready endpoints. No private or deprecated APIs.

> **Note**: APIs evolve rapidly. Check [issues](https://github.com/ishandutta2007/awesome-ai-apis/issues) for updates. Contributions welcome!

## Table of Contents 📖

- [LLM & Chat APIs](#llm--chat-apis)
- [Image Generation](#image-generation)
- [Speech & Audio](#speech--audio)
- [Vision & Multimodal](#vision--multimodal)
- [Embeddings & Vector DB](#embeddings--vector-db)
- [Agents & Tools](#agents--tools)
- [Other AI](#other-ai)

**Back to top** ⬆️ • [Contribute](#contributing) • [License](#license)

## LLM & Chat APIs 💬

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [OpenAI](https://platform.openai.com/docs/api-reference) | GPT-4o, o1, GPT-5 series for text, reasoning, vision, voice. Free tier available. | `apiKey` | Yes | Yes |
| [Anthropic Claude](https://docs.anthropic.com/en/api/getting-started) | Claude 3.5 Sonnet, Opus for advanced reasoning & coding. | `apiKey` | Yes | Yes |
| [xAI Grok](https://docs.x.ai/) | Grok-4 for real-time reasoning, math, vision. Integrated with X data. | `apiKey` | Yes | Yes |
| [Google Gemini](https://ai.google.dev/) | Gemini 2.0 Flash/Pro for multimodal, low-latency apps. Free tier. | `apiKey` | Yes | Yes |
| [Mistral AI](https://docs.mistral.ai/api/) | Mistral Large 2, Mixtral for efficient multilingual tasks. Open weights. | `apiKey` | Yes | Yes |
| [Meta Llama](https://llama.meta.com/) | Llama 4 Scout/Maverick via partners (e.g., Groq, Replicate). Open-source. | Varies | Yes | Yes |
| [Cohere](https://docs.cohere.com/docs) | Command R+ for RAG, enterprise chat. Free prototyping. | `apiKey` | Yes | Yes |
| [Groq](https://console.groq.com/docs/api-reference) | Ultra-fast inference for Llama, Mixtral, Gemma. 1000 req/day free. | `apiKey` | Yes | Yes |
| [Together AI](https://docs.together.ai/docs) | 300+ open models (Qwen, DeepSeek). Free credits. | `apiKey` | Yes | Yes |
| [DeepInfra](https://deepinfra.com/docs) | Affordable hosting for Llama, Mistral. Pay-per-use. | `apiKey` | Yes | Yes |
| [CoderPlan](https://coderplan.ai) | Unified LLM API gateway for Claude, GPT, Gemini, DeepSeek, Grok. OpenAI-compatible. Pay-per-use with Alipay/WeChat. | `apiKey` | Yes | Yes |

**Back to Index** 👆 👆

## Image Generation 🖼️

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [Stability AI](https://platform.stability.ai/docs/api-reference) | Stable Diffusion 3, Flux for text-to-image. Free tier. | `apiKey` | Yes | Yes |
| [Replicate](https://replicate.com/docs) | Run Flux, SDXL, custom models. $5 free credits. | `apiKey` | Yes | Yes |
| [OpenAI DALL-E](https://platform.openai.com/docs/api-reference/images) | DALL-E 3 for high-quality images. | `apiKey` | Yes | Yes |

**Back to Index** 👆 👆

## Speech & Audio 🎤

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [OpenAI TTS/Whisper](https://platform.openai.com/docs/api-reference/audio) | Text-to-speech, speech-to-text. | `apiKey` | Yes | Yes |
| [ElevenLabs](https://elevenlabs.io/docs/api-reference) | Voice cloning, TTS. Free tier. | `apiKey` | Yes | Yes |
| [Deepgram](https://developers.deepgram.com/docs) | Real-time STT with diarization. | `apiKey` | Yes | Yes |

**Back to Index** 👆 👆

## Vision & Multimodal 👀

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [OpenAI Vision](https://platform.openai.com/docs/vision) | GPT-4V for image analysis. | `apiKey` | Yes | Yes |
| [Google Gemini Vision](https://ai.google.dev/gemini-api/docs/vision) | Multimodal reasoning. | `apiKey` | Yes | Yes |
| [Hugging Face Inference](https://huggingface.co/docs/inference-endpoints) | Llava, Bakllava for open vision models. Free limited. | `apiKey` | Yes | Unknown |

**Back to Index** 👆 👆

## Embeddings & Vector DB 🧠

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) | Text-embedding-3-large. | `apiKey` | Yes | Yes |
| [Cohere Embed](https://docs.cohere.com/docs/embed) | Multilingual embeddings. | `apiKey` | Yes | Yes |
| [Pinecone](https://docs.pinecone.io/docs/overview) | Vector DB with hybrid search. Free starter. | `apiKey` | Yes | Yes |

**Back to Index** 👆 👆

## Agents & Tools 🛠️

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [OpenAI Assistants](https://platform.openai.com/docs/assistants/overview) | Custom agents with tools/files. | `apiKey` | Yes | Yes |
| [Replicate Agents](https://replicate.com/docs/guides/agents) | Run agentic workflows. | `apiKey` | Yes | Yes |
| [Voidly Pay](https://voidly.ai/pay) | x402 facilitator + agent payment rail (escrow, streams, subscriptions) with marketplace of 17 paid endpoints. USDC on Base. | `x402` (no apiKey) | Yes | Yes |

**Back to Index** 👆 👆

## Other AI ✨

| API | Description | Auth | HTTPS | CORS |
|-----|-------------|------|-------|------|
| [Hugging Face Hub](https://huggingface.co/docs/hub/en/api) | 1M+ models for tasks like NER, translation. | `apiKey` (opt) | Yes | Yes |

**Back to Index** 👆 👆

## How to Contribute 🤝

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

1. **Add an API**: Fork, edit README.md table. Use format: `[Name](link) | Desc | Auth | Yes/No | Yes/No/Unknown`
2. **Categories**: Suggest new ones via issues.
3. **Verify**: APIs must be live, public docs, preferably free tier.
4. **No Self-Promo**: Community-only.

## Stats

![Contributors](https://img.shields.io/github/contributors/ishandutta2007/awesome-ai-apis)  
![Issues](https://img.shields.io/github/issues/ishandutta2007/awesome-ai-apis)

## License 📜

This repo is [MIT licensed](LICENSE).

---

*Built with ❤️ by the AI community. Started Jan 12, 2026.*

---

## Other Files & Folders 📁

### Folder Structure
```
awesome-ai-apis/
├── README.md                 # Main file (above)
├── CONTRIBUTING.md           # Below
├── LICENSE                   # MIT
├── .gitignore                # Standard
└── .github/
    └── ISSUE_TEMPLATE.md     # Below
```

Copy these into your repo @ https://github.com/ishandutta2007/awesome-ai-apis. Add APIs via PRs to grow it! 🌟
