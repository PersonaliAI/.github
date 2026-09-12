<div align="center">

<img src="https://raw.githubusercontent.com/PersonaliAI/.github/main/profile/assets/header-banner.svg" alt="PersonaliAI Header Banner" width="100%">

<br/>
<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Status: Production Ready](https://img.shields.io/badge/Status-Production--Ready-10b981.svg?style=for-the-badge&logo=checkmarx&logoColor=white)](https://chatty.personaliai.com)
[![Voice: LiveKit WebRTC](https://img.shields.io/badge/Voice-LiveKit--WebRTC-38bdf8.svg?style=for-the-badge&logo=webrtc&logoColor=white)](https://github.com/PersonaliAI/ai-voice-agents)
[![Architecture: Multi--Agent](https://img.shields.io/badge/Architecture-Multi--Agent-8b5cf6.svg?style=for-the-badge&logo=diagram-project&logoColor=white)](#-system-architecture)
[![Docs](https://img.shields.io/badge/Docs-docs.chatty.personaliai.com-06b6d4.svg?style=for-the-badge&logo=bookstack&logoColor=white)](https://docs.chatty.personaliai.com)

<br/>

### Industrial-grade, open-source AI conversational platforms & real-time voice agents.

**[🌐 Website](https://chatty.personaliai.com)** &nbsp;•&nbsp; **[📚 Documentation](https://docs.chatty.personaliai.com)** &nbsp;•&nbsp; **[🚀 Chatty Cloud](https://chatty.personaliai.com)** &nbsp;•&nbsp; **[📦 Integration SDKs](#-cross-platform-sdk-ecosystem)** &nbsp;•&nbsp; **[🏗️ Architecture](#-system-architecture)**

</div>

---

## 🚀 Executive Summary

**PersonaliAI** engineers production-ready, open-source conversational AI infrastructure designed for enterprise deployment, privacy sovereignty, and real-time multimodal interaction.

Our platform bridges state-of-the-art Large Language Models (LLMs), low-latency WebRTC audio workers, vector knowledge retrieval (RAG), and native cross-platform SDKs into a cohesive multi-agent ecosystem. Whether deployed via **1-click Docker self-hosting** or integrated through native mobile SDKs, PersonaliAI empowers teams to deliver autonomous voice and chat assistants without data lock-in.

---

## 🏗️ System Architecture

PersonaliAI utilizes a decoupled, event-driven architecture designed for high throughput, sub-second latency voice pipelines, and multi-tenant isolation.

<div align="center">

<img src="https://raw.githubusercontent.com/PersonaliAI/.github/main/profile/assets/architecture-diagram.svg" alt="PersonaliAI System Architecture" width="100%">

</div>

### Key Architectural Layers

* **Omni-Channel Distribution**: Native UI SDKs across Web, iOS, Android, React Native, Flutter, and WordPress with 100% feature parity.
* **Core Agent Engines**: Next.js 15 & FastAPI orchestrator powering stateful conversations, document RAG, automated scheduling, and human agent takeover.
* **Real-Time Voice Matrix**: LiveKit WebRTC media transport paired with Silero Voice Activity Detection (VAD) and LiteLLM streaming.
* **Storage & Infrastructure**: Self-contained PostgreSQL with `pgvector` extension, Redis session cache, and BYOK (Bring Your Own Key) model routing.

---

## ⚡ Core Platform Repositories

| Repository | Purpose & Capabilities | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| **[💬 chatty](https://github.com/PersonaliAI/chatty)** | Open-source AI customer support platform featuring document RAG, automated calendar booking (Google Meet/Zoom), real-time LiveKit voice, multi-workspace administration, and live human agent takeover. | Next.js 15, FastAPI, PostgreSQL + pgvector, Tailwind CSS | ![Active](https://img.shields.io/badge/Active-10b981?style=flat-square) |
| **[🧬 kin](https://github.com/PersonaliAI/kin)** | Autonomous personal executive AI assistant managing email workflows, calendar scheduling, and daily task orchestration with long-term semantic memory. | Python, LiteLLM, Redis, Vector Memory | ![Active](https://img.shields.io/badge/Active-10b981?style=flat-square) |
| **[🎙️ ai-voice-agents](https://github.com/PersonaliAI/ai-voice-agents)** | High-concurrency WebRTC audio worker connecting real-time voice agents directly to live phone/voice channels, Telegram, and WhatsApp. | LiveKit, Silero VAD, WebRTC, Asyncio | ![Active](https://img.shields.io/badge/Active-10b981?style=flat-square) |

---

## 📦 Cross-Platform SDK Ecosystem

Embed full-featured AI support chat and real-time voice directly into your applications with zero webviews or performance degradation.

```
                  ┌──────────────────────────────────────────┐
                  │          PersonaliAI Core Platform       │
                  └─────────────────────┬────────────────────┘
                                        │
      ┌──────────────┬──────────────┬───┴──────────┬──────────────┬──────────────┐
      │              │              │              │              │              │
 🌐 Web Script   ⚛️ React Native 💙 Flutter     🤖 Android       🍎 iOS     🔌 WordPress
```

### SDK Feature Matrix

| Platform | Package / Method | Native UI | WebRTC Voice | Document RAG | Installation |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **Web** | Shadow DOM Script Tag | Yes | Yes | Yes | `<script src="https://chatty.personaliai.com/widget.js" data-id="BOT_ID" defer></script>` |
| **React Native** | [`@personaliai/react-native`](https://github.com/PersonaliAI/chatty-react-native-sdk) | Yes | Yes | Yes | `npm install @personaliai/react-native` |
| **Flutter** | [`chatty_flutter`](https://github.com/PersonaliAI/chatty-flutter-sdk) | Yes | Yes | Yes | `flutter pub add chatty_flutter` |
| **Android** | [`chatty-android-sdk`](https://github.com/PersonaliAI/chatty-android-sdk) | Jetpack Compose | Yes | Yes | `implementation 'com.personaliai:chatty-android:1.0.0'` |
| **iOS** | [`chatty-ios-sdk`](https://github.com/PersonaliAI/chatty-ios-sdk) | SwiftUI | Yes | Yes | `.package(url: "https://github.com/PersonaliAI/chatty-ios-sdk")` |
| **WordPress** | [`chatty-wordpress-plugin`](https://github.com/PersonaliAI/chatty-wordpress-plugin) | Yes | Yes | Yes | Download `.zip` or install via WP Admin Directory |

---

## 🛡️ Enterprise Capabilities

<table>
  <tr>
    <td width="50%">
      <h3>🔒 100% Data Sovereignty</h3>
      <p>Deploy completely air-gapped or on self-hosted infrastructure (AWS, GCP, Azure, bare-metal). Zero mandatory cloud dependencies, no third-party telemetry, and full control over customer conversation storage.</p>
    </td>
    <td width="50%">
      <h3>⚡ Low-Latency Multimodal Voice</h3>
      <p>Sub-500ms voice-to-voice response loops via LiveKit WebRTC audio channels. Built-in neural Voice Activity Detection (VAD) and interruption handling for fluid, natural dialogue.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📚 Advanced Document RAG</h3>
      <p>Automated vector ingestion for PDFs, Markdown, Notion, websites, and database dumps using <code>pgvector</code>. Dynamic contextual retrieval with hybrid keyword + semantic re-ranking.</p>
    </td>
    <td width="50%">
      <h3>🔑 Multi-LLM BYOK Architecture</h3>
      <p>Switch seamlessly between OpenAI (GPT-4o), Anthropic (Claude 3.5 Sonnet), Google Gemini, Groq (Llama 3), and local Ollama models with automated fallback routing.</p>
    </td>
  </tr>
</table>

---

## 🛠️ Quickstart Deployment

### 1. Docker Self-Host (Chatty Platform)

Spin up the full Chatty platform with PostgreSQL, pgvector, and LiveKit voice support in under 2 minutes:

```bash
git clone https://github.com/PersonaliAI/chatty.git
cd chatty
cp .env.example .env
docker compose up -d
```

Access your admin console at `http://localhost:3000`.

### 2. Embed Web Chat Widget

Paste into any HTML site, Webflow, Shopify, or React app:

```html
<script
  src="https://chatty.personaliai.com/widget.js"
  data-id="YOUR_BOT_ID"
  defer>
</script>
```

---

## 🤝 Open Source Governance & Community

PersonaliAI is committed to maintaining open, accessible, and enterprise-grade software.

* **Bug Reports & Feature Requests**: Open an issue on the relevant repository ([chatty](https://github.com/PersonaliAI/chatty/issues), [kin](https://github.com/PersonaliAI/kin/issues), or [ai-voice-agents](https://github.com/PersonaliAI/ai-voice-agents/issues)).
* **Security Disclosures**: Report security vulnerabilities privately to `security@personaliai.com`.
* **License**: All core repositories are licensed under the permissive [MIT License](LICENSE).

<br/>

<div align="center">

<sub>Designed & Built by PersonaliAI Core Team · © 2026 PersonaliAI</sub>

</div>
