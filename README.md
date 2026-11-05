<!--
description: A collaborative and community-maintained list of publicly available AI APIs for developers, researchers, and enthusiasts, covering LLMs, image generation, speech, vision, and more.
keywords: AI APIs, machine learning APIs, artificial intelligence, LLM APIs, image generation APIs, speech APIs, vision APIs, open-source AI, free AI APIs, developer tools, AI integrations, awesome list
-->
# Awesome AI APIs 🚀

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/awesome-ai-apis?style=social)](https://github.com/ishandutta2007/awesome-ai-apis/stars/0) [![GitHub forks](https://img.shields.io/github/forks/ishandutta2007/awesome-ai-apis?style=social)](https://github.com/ishandutta2007/awesome-ai-apis/network/members) [![GitHub contributors](https://img.shields.io/github/contributors/ishandutta2007/awesome-ai-apis)](https://github.com/ishandutta2007/awesome-ai-apis/graphs/contributors) [![GitHub issues](https://img.shields.io/github/issues/ishandutta2007/awesome-ai-apis)](https://github.com/ishandutta2007/awesome-ai-apis/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/ishandutta2007/awesome-ai-apis)](https://github.com/ishandutta2007/awesome-ai-apis/pulls) [![GitHub last commit](https://img.shields.io/github/last-commit/ishandutta2007/awesome-ai-apis)](https://github.com/ishandutta2007/awesome-ai-apis/commits/main) [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ishandutta2007/awesome-awesome-awesome)

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

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [OpenAI](https://platform.openai.com/docs/api-reference) | GPT-4o, o1, GPT-5 series for text, reasoning, vision, voice. | Starting at $0.15/1M input, $0.60/1M output tokens (GPT-4o mini) | Pay-as-you-go ($5 min deposit); no recurring free tier. ChatGPT Pro/Business get $100–$500/mo API credits | `apiKey` | Yes | Yes |
| [Anthropic Claude](https://docs.anthropic.com/en/api/getting-started) | Claude 3.5 Sonnet, Opus for advanced reasoning & coding. | Starting at $0.25/1M input, $1.25/1M output tokens (Claude 3.5 Haiku) | $5 one-time promotional sign-up credits (valid for initial testing); no recurring free tier | `apiKey` | Yes | Yes |
| [xAI Grok](https://docs.x.ai/) | Grok-4 for real-time reasoning, math, vision. Integrated with X data. | Starting at $2.00/1M input, $10.00/1M output tokens (Grok-2) | Up to $150/mo free credits via opt-in data-sharing program (after $5 initial spend; regional restrictions apply) | `apiKey` | Yes | Yes |
| [Google Gemini](https://ai.google.dev/) | Gemini 2.0 Flash/Pro for multimodal, low-latency apps. | Starting at $0.10/1M input, $0.40/1M output tokens (Gemini 2.0 Flash pay-as-you-go) | Free forever on Google AI Studio: 15 RPM, 1M TPM, 1,500 RPD (Gemini Flash models, prompts used for training) | `apiKey` | Yes | Yes |
| [Mistral AI](https://docs.mistral.ai/api/) | Mistral Large 2, Mixtral for efficient multilingual tasks. Open weights. | Starting at $0.10/1M input, $0.10/1M output tokens (Ministral 3B) / $0.15 in, $0.60 out (Mistral Small) | Free experimental mode on La Plateforme: 1 req/sec, ~30 RPM cap across available models | `apiKey` | Yes | Yes |
| [Meta Llama](https://llama.meta.com/) | Llama 4 Scout/Maverick via partners (e.g., Groq, Replicate). Open-source. | Free self-hosted open weights; partner hosted starting at $0.05/1M tokens | Open weights free for download; hosted free tiers vary by provider (e.g., Groq 30 RPM free) | Varies | Yes | Yes |
| [Cohere](https://docs.cohere.com/docs) | Command R+ for RAG, enterprise chat. Free prototyping. | Starting at $0.15/1M input, $0.60/1M output tokens (Command R) | Free forever Trial Key for non-commercial evaluation: 1,000 calls/month, 20 RPM on Chat | `apiKey` | Yes | Yes |
| [Groq](https://console.groq.com/docs/api-reference) | Ultra-fast inference for Llama, Mixtral, Gemma. | Starting at $0.05/1M input, $0.08/1M output tokens (Llama 3.1 8B) | Free forever plan: 30 RPM, up to 30,000 TPM, and 100,000–500,000 TPD (model-dependent) | `apiKey` | Yes | Yes |
| [Together AI](https://docs.together.ai/docs) | 300+ open models (Qwen, DeepSeek). Free credits. | Starting at $0.15/1M input, $0.60/1M output tokens (Llama/Flash models) | $5 min reload ($15 initial credit purchase); startup accelerator provides $15k–$50k grants on approval | `apiKey` | Yes | Yes |
| [DeepInfra](https://deepinfra.com/docs) | Affordable hosting for Llama, Mistral. Pay-per-use. | Starting at $0.03/1M input, $0.05/1M output tokens (Llama 3.1 8B) | $1.80 free trial credits on new account sign-up and verification; no monthly subscription | `apiKey` | Yes | Yes |
| [CoderPlan](https://coderplan.ai) | Unified LLM API gateway for Claude, GPT, Gemini, DeepSeek, Grok. OpenAI-compatible. Pay-per-use with Alipay/WeChat. | Non-expiring prepaid packages starting at $7.14 for $50 credit balance | One-time signup promotional test credits for initial evaluation; no recurring free tier | `apiKey` | Yes | Yes |

**Back to Index** 👆

## Image Generation 🖼️

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [Stability AI](https://platform.stability.ai/docs/api-reference) | Stable Diffusion 3, Flux for text-to-image. | Starting at $0.03/image (3 credits) for SD 3.5 Large / $0.02 for edits | 25 free credits ($0.25 value, ~8–12 standard generations) upon signup; no recurring monthly quota | `apiKey` | Yes | Yes |
| [Replicate](https://replicate.com/docs) | Run Flux, SDXL, custom models. | Hardware compute starting at $0.00025/sec (CPU) / $0.001525/sec (GPU), or ~$0.003–$0.04/image (Flux) | Limited free trial predictions in web playground/demo mode (throttled at 1 req/sec, 6 RPM max); no recurring free tier | `apiKey` | Yes | Yes |
| [OpenAI DALL-E](https://platform.openai.com/docs/api-reference/images) | DALL-E 3 for high-quality images. | Starting at $0.040/image (standard 1024×1024) / $0.080/image (HD quality) | Pay-as-you-go ($5 min deposit); no recurring free tier credits | `apiKey` | Yes | Yes |

**Back to Index** 👆

## Speech & Audio 🎤

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [OpenAI TTS/Whisper](https://platform.openai.com/docs/api-reference/audio) | Text-to-speech, speech-to-text. | Whisper STT at $0.006/minute ($0.36/hour); TTS starting at $0.015/1k characters | Pay-as-you-go ($5 min deposit); no recurring free tier | `apiKey` | Yes | Yes |
| [ElevenLabs](https://elevenlabs.io/docs/api-reference) | Voice cloning, TTS. | Paid starter plan at $5/month (first month $1) for 30,000 characters | Free forever tier: 10,000 characters/month (~10 mins audio), non-commercial attribution required, 3 custom voices | `apiKey` | Yes | Yes |
| [Deepgram](https://developers.deepgram.com/docs) | Real-time STT with diarization. | Pre-recorded STT starting at $0.0043/min; streaming at $0.0048/min; TTS at $0.015/1k characters | $200 free trial credits upon sign-up (no credit card required, up to 150 concurrent streams) | `apiKey` | Yes | Yes |

**Back to Index** 👆

## Vision & Multimodal 👀

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [OpenAI Vision](https://platform.openai.com/docs/vision) | GPT-4o multimodal image analysis. | Starting at $0.15/1M input tokens + $0.001275/standard low-res tile (GPT-4o mini) | Pay-as-you-go ($5 min deposit); no recurring free tier | `apiKey` | Yes | Yes |
| [Google Gemini Vision](https://ai.google.dev/gemini-api/docs/vision) | Multimodal reasoning for images and video. | Starting at $0.10/1M input tokens (Gemini 2.0 Flash pay-as-you-go) | Free forever on Google AI Studio: 15 RPM, 1M TPM, 1,500 RPD (Flash multimodal tier) | `apiKey` | Yes | Yes |
| [Hugging Face Inference](https://huggingface.co/docs/inference-endpoints) | Llava, Bakllava for open vision models. | Dedicated endpoints start at $0.06/hour (CPU) to $0.60+/hour (GPU); PRO plan $9/month | Serverless inference free tier provides ~$0.10/mo in inference credits (rate-limited, hard stop when exhausted) | `apiKey` | Yes | Unknown |

**Back to Index** 👆

## Embeddings & Vector DB 🧠

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) | Text-embedding-3-small and large. | Starting at $0.02/1M input tokens (text-embedding-3-small) / $0.13/1M (large) | Pay-as-you-go ($5 min deposit); no recurring free tier | `apiKey` | Yes | Yes |
| [Cohere Embed](https://docs.cohere.com/docs/embed) | Multilingual embeddings & Rerank. | Starting at $0.10/1M tokens (Embed v3 English/Multilingual) | Free forever Trial Key: 1,000 API calls/month, 100 RPM for Embed endpoints (non-commercial) | `apiKey` | Yes | Yes |
| [Pinecone](https://docs.pinecone.io/docs/overview) | Vector DB with hybrid search. | Paid Builder plan at $20/month; Standard pay-as-you-go from $0.0825/GB-month | Free forever Starter tier: 2 GB storage (~100k 1536-dim vectors), 1M read units/mo, 2M write units/mo, 5 indexes | `apiKey` | Yes | Yes |

**Back to Index** 👆

## Agents & Tools 🛠️

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [OpenAI Assistants](https://platform.openai.com/docs/assistants/overview) | Custom agents with tools/files. | Base token pricing (from $0.15/1M tokens) + Code Interpreter ($0.03/session) + File Search ($0.10/GB/day) | Pay-as-you-go ($5 min deposit); File Search includes 1 GB free storage per organization | `apiKey` | Yes | Yes |
| [Replicate Agents](https://replicate.com/docs/guides/agents) | Run agentic workflows. | Compute-based execution starting at $0.00025/sec CPU / $0.001525/sec GPU | Limited playground free runs (throttled at 1 req/sec, 6 RPM max) | `apiKey` | Yes | Yes |
| [Voidly Pay](https://voidly.ai/pay) | x402 facilitator + agent payment rail with marketplace of 17 paid endpoints. USDC on Base. | Micropayments starting from $0.001 USDC per API call / stream | Testnet sandbox & faucet available with free mock USDC; protocol discovery free | `x402` (no apiKey) | Yes | Yes |
| [Superhighway](https://superhighway.walls.sh) | Web search API for agents: search, news, images, scrape, research endpoints. MCP server `npx -y superhighway-mcp`. | Pay-per-call from $0.001–$0.005 USDC via x402 | Free forever API key tier with generous daily search queries; free discovery without account | `apiKey` / `x402` | Yes | Yes |
| [Clarity](https://agent-tools.cloud/services/desktop-o99r0sf-tail935fba-ts-net-sub899) | Base mainnet x402 research report ($2 USDC) + OpenAI-compatible chat ($0.001) APIs. External Base USDC payers only. | $0.001 USDC per chat call, $2.00 USDC per deep research report | Free `/.well-known/x402` and agent metadata discovery endpoints (0 USDC) | `x402` (no apiKey) | Yes | Unknown |
| [GoldBean](https://goldbean-api.xyz) | 53 Chinese AI tools via x402 micropayments — 19 OCR types, ERNIE LLM, DeepSeek-R1, TTS, ASR, vision, NLP, translation. | Micropayments starting from $0.001/call (TTS) to $0.01/call (OCR) via Base USDC or Alipay | Free forever plan: 2,000 calls/day per IP (standard endpoints) and 50 calls/day (test tools), no signup needed | `x402` (no apiKey) | Yes | Yes |

**Back to Index** 👆

## Other AI ✨

| API | Description | Pricing | Free Tier / Trial Limits | Auth | HTTPS | CORS |
|-----|-------------|---------|--------------------------|------|-------|------|
| [Hugging Face Hub](https://huggingface.co/docs/hub/en/api) | 1M+ models and datasets for tasks like NER, translation. | Free community hosting; PRO user tier at $9/month | Free forever: 1,000 API requests per 5-min window, 5,000 resolver/download requests per 5-min window | `apiKey` (opt) | Yes | Yes |

**Back to Index** 👆

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
