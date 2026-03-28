# ABOV3 EXODUS GUIDE/FAQ

## Introduction

**Advanced AI Workspace for Multi-Model Reasoning, Coding, and Research**

The ABOV3 Exodus Agentic Development environment  is a next-generation AI workspace built for professionals who demand more from their AI tools.

The ABOV3 Exodus Agentic Development environment provides a full environment (including MCP) for air-gapped or connected development.  
1) It can work with local directories for code or document development
2) Utilize your inference source - or ABOV3's own models
3) Supports many agents and the Prism "swarm" where a problem can be submitted to multiple models simultaneously and then an arbiter merges them into a "best of breed" response.  You can also create customized agents and sub-agents if the stock agents aren't sufficient.
4) Flowcore supports development of agent-driven processes that are somewhat rigid and well defined.
5) Naphesh supports the development of true AGI - agents that are flexible and can perform a diverse set of tasks.  You can speak with them, or text them from your phone.  What they can do is entirely what you're willing to give them permission to do.

** Note - ABOV3 uses its own VOIP to ensure that caller-ID spoofing will not work, only the true and verified phone number can text its agent.

**What makes ABOV3 Exodus different:**
**Intelligence** with Beam & Merge for multi-model reasoning and bleeding-edge AI models - **Control** with personas, data ownership, unlimited usage with your API keys, and *no vendor lock-in* - **Speed** with a local-first, over-powered, zero-latency web application.

**Who uses ABOV3 Exodus:**
Built for engineers, founders, researchers, self-hosters, and IT departments who need power, reliability, and transparency.

## ✨ Features

### 🎯 Multi-Model AI (Beam)
- **Parallel Processing**: Run multiple AI models simultaneously
- **Compare & Merge**: Intelligent fusion of responses from different models
- **Save Presets**: Reuse your best model combinations

### 🤖 100+ AI Models Supported
- **OpenAI**: GPT-4, GPT-4 Turbo, o1, o3
- **Anthropic**: Claude 4.5 Sonnet, Claude 3.5 Haiku, Claude Opus
- **Google**: Gemini 2.0, Gemini 2.5 Flash, Gemini 2.0 Flash Thinking
- **Open Source**: Ollama, LM Studio, LocalAI
- **Cloud Providers**: Azure OpenAI, AWS Bedrock, OpenRouter
- And many more...

### 🎭 Advanced Persona System
- Pre-built professional personas (Developer, Scientist, Executive, etc.)
- Custom persona creator with AI-assisted generation
- Context-aware responses based on selected persona

### 🖼️ Image Generation & Editing
- Integrated image generation with DALL-E and other providers
- Multi-image editing and enhancement
- Built-in prompt engineering assistance

### 🔍 Web Search & Browse
- Real-time web search with citations
- Page content extraction and analysis
- YouTube transcript integration

### 🎙️ ABOV3 Pauline TTS (New!)
- **Self-Hosted TTS**: Professional text-to-speech with 28 voices
- **GPU Accelerated**: CUDA, ROCm, and CPU support
- **High Quality**: Natural-sounding voice synthesis
- **Real-time Streaming**: Low-latency audio generation
- **Privacy-First**: All processing happens locally
- **Easy Setup**: One-command Docker deployment

[Read More](./pauline.md)

### 🏛️ ABOV3 Ark LocalAI (New!)
- **Self-Hosted LLMs**: Run Mistral models locally with full privacy
- **GPU Accelerated**: CUDA, ROCm, and CPU support
- **3 Curated Models**: OpenHermes-2.5, Mistral-OpenOrca, Nous-Hermes-2
- **Model Gallery**: Easy installation via UI or API
- **OpenAI Compatible**: Drop-in replacement for OpenAI API
- **No Cloud Dependencies**: All inference happens on your hardware

[Read More](./ark_page.md)

### Flowcore Operations

Coming soon, flowcore.

[Read More](./flowcore_into.md)

### 📁 File Operations
- **Read/Write Files**: AI can read and modify files in your project
- **Directory Management**: Create directories and organize files
- **Project Integration**: Select any local directory for AI assistance
- **Browser-Native**: Uses File System Access API (Chrome, Edge, Safari)
- **Visual Indicator**: Green chip shows when file tools are active

### 💾 Data Ownership & Privacy
- **Local-First Architecture**: Your data stays on your device
- **No Vendor Lock-In**: Use your own API keys
- **Full Export/Import**: Backup and restore conversations
- **IndexedDB Storage**: Fast, efficient local storage

### ⚡ Performance Optimized
- Zero-latency UI updates
- Streaming responses from all providers
- Efficient token counting and cost tracking
- Mobile-responsive design

### 🎨 Professional UI
- ABOV3-branded modern interface
- Custom animated persona icons
- Dark mode optimized
- Split-pane multi-conversation support



# FAQ Topics
## Inference Source Integration

### Claude (Anthropic) Pro and Enterprise
Exodus supports both pre-paid API token accounts, as well as Claude Pro and Enterprise accounts.  If you intend to do code development, the Pro/Enterprise accounts will work well, but if you intend to develop long-running agents (Flow/Nephesh) the short lifespan of the Claude Pro/Enterprise tokens makes this almost impossible (they expire in about 6 hours).

To enable your Claude Pro/Enterprise with Exodus, follow [these steps](./claude_jwt_tokens.md)

