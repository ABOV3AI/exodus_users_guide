# ABOV3 Pauline TTS: Professional Voice Synthesis Platform

**Enterprise-grade text-to-speech server with voice cloning, audiobook generation, and OpenAI-compatible API.**

> 🎙️ **ABOV3 Pauline** delivers crystal-clear, professional voice synthesis optimized for production deployment. Features include intelligent text processing, 28 production-ready voices, and seamless integration with your existing workflows.

## 🗣️ Overview

ABOV3 Pauline TTS provides enterprise-grade text-to-speech capabilities with voice cloning, large text processing, and audiobook generation. Key features include:

*   A **modern Web UI** for easy experimentation, voice management, and generation parameter tuning
*   **Multi-Platform Acceleration:** Full support for **NVIDIA (CUDA)**, **AMD (ROCm)**, and **Apple Silicon (MPS)** GPUs with automatic **CPU** fallback
*   **Large Text Handling:** Intelligently splits long texts into manageable chunks based on sentence structure and seamlessly concatenates audio
*   **📚 Audiobook Generation:** Create complete audiobooks from full-length texts with consistent voice quality
*   **28 Predefined Voices:** Curated, production-ready synthetic voices for immediate use
*   **Voice Cloning:** Generate speech using uploaded reference audio files
*   **Optimized Audio Quality:** Pre-configured with professional settings for calm, clear delivery (temperature: 0.6, exaggeration: 0.8, cfg_weight: 0.7)
*   **Docker Support:** One-command deployment with GPU acceleration

## ✨ Key Features

**🚀 Core Functionality:**

*   **Large Text Processing (Chunking):**
    *   Automatically handles long plain text by splitting into sentence-based chunks
    *   Ideal for **audiobook generation** - paste entire books and get professional narration
    *   Configurable chunk size and split toggle in UI
*   **28 Production-Ready Voices:**
    *   Includes Emily, Gabriel, Olivia, and 25 more curated voices
    *   Categorized by style (professional, friendly, authoritative, etc.)
    *   Stored in library, selectable via UI dropdown
*   **Voice Cloning:**
    *   Clone any voice using reference audio (`.wav` or `.mp3`)
    *   Upload reference files through Web UI
*   **Optimized Generation:**
    *   Pre-configured for calm, professional delivery
    *   Adjustable temperature, exaggeration, CFG weight, seed, and speed
    *   Consistent voice output across generations

**🔧 Enhanced Server Features:**

*   **OpenAI-Compatible API:** Drop-in replacement for OpenAI TTS endpoints
*   **Audio Post-Processing:** Optional silence trimming and artifact removal
*   **Session Persistence:** Remembers UI settings 
*   **Light/Dark Mode:** Theme toggle with preference saved

**🌐 Web Interface:**

*   Modern, responsive UI with intuitive controls
*   Preset loading from `ui/presets.yaml`
*   Reference/predefined audio upload and management
*   Real-time audio playback with waveform visualization
*   Configuration management directly in UI
*   Warning modals for generation quality

## 💡 Usage

### Web UI

*   **Text Input:** Enter text or paste entire book for audiobook generation
*   **Voice Mode:** Choose from 28 predefined voices or use voice cloning
*   **Parameters:** Adjust temperature, exaggeration, speed, seed
*   **Chunking:** Enable for long texts with adjustable chunk size
*   **Audio Player:** Play generated audio with waveform, download option

