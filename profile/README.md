<div align="center">

<img src="https://raw.githubusercontent.com/PersonaliAI/.github/main/profile/assets/personali-logo-white-bg.png" alt="PersonaliAI" width="360" />

<br/>
<br/>

### AI tools built for your life & work.

*Open-source conversational platforms, real-time voice agents, and developer-first SDKs.*

<br/>

[Website](https://chatty.personaliai.com) &nbsp;·&nbsp; [Documentation](https://docs.chatty.personaliai.com) &nbsp;·&nbsp; [Chatty Cloud](https://chatty.personaliai.com) &nbsp;·&nbsp; [Docker Hub](https://hub.docker.com/u/personaliai)

</div>

---

### Flagship Platform: Chatty

[Chatty](https://github.com/PersonaliAI/chatty) is an open-source, production-grade AI customer support platform. It unifies web chat, real-time voice, document grounding, and an MCP server under a single deployment.

- **Embeddable Chat Widget**: Drop-in web component with session persistence, lead capture, and custom theme overrides.
- **Real-Time Voice Agent**: Sub-500ms conversational audio powered by LiveKit WebRTC and speech-to-speech pipelines.
- **Document RAG Engine**: Instant knowledge grounding via PDF, TXT, DOCX, and live website crawling.
- **Model Context Protocol (MCP)**: Native FastMCP server providing external AI coding tools direct access to bot auditing and knowledge management.
- **Conversational Actions**: Automated calendar booking (Google Meet and Zoom) and webhook dispatch.
- **Hybrid Self-Hosting**: Deploy application containers on your own host while keeping Supabase Auth and Postgres managed.

```html
<!-- 3-line drop-in web embed -->
<script
  src="https://chatty.personaliai.com/widget.js"
  data-id="YOUR_BOT_ID"
  defer>
</script>
```

---

### Client SDKs

Native mobile and web packages with feature parity and zero third-party UI dependencies:

| Platform | Repository | Package / Artifact |
|:---|:---|:---|
| Web | [chatty](https://github.com/PersonaliAI/chatty) | `https://chatty.personaliai.com/widget.js` |
| React | [chatty-react](https://github.com/PersonaliAI/chatty/tree/main/packages/chatty-react) | `@personaliai/chatty-react` |
| React Native | [chatty-react-native-sdk](https://github.com/PersonaliAI/chatty-react-native-sdk) | `@personaliai/react-native` |
| Flutter | [chatty-flutter-sdk](https://github.com/PersonaliAI/chatty-flutter-sdk) | `chatty_flutter` |
| iOS (SwiftUI) | [chatty-ios-sdk](https://github.com/PersonaliAI/chatty-ios-sdk) | `ChattySDK` |
| Android (Compose) | [chatty-android-sdk](https://github.com/PersonaliAI/chatty-android-sdk) | `com.personaliai.chatty` |
| WordPress | [chatty-wordpress-plugin](https://github.com/PersonaliAI/chatty-wordpress-plugin) | `chatty-support` |

---

<div align="center">

<sub>Open source under the <a href="https://github.com/PersonaliAI/chatty/blob/main/LICENSE">MIT License</a> · © 2026 PersonaliAI</sub>

</div>
