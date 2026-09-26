💬 NOVIQ

A minimal, self-hosted chat interface that connects to any OpenAI-compatible or Anthropic-compatible AI endpoint — configure your own API, .

✨ Features

- 🔌 **Bring your own backend** — connect to any OpenAI-compatible (`/chat/completions`) or Anthropic-compatible (`/v1/messages`) API by entering a base URL, API key, and model
- 🏷️ **Custom agent name** — name your agent and it will identify itself by that name when asked
- 💾 **Persistent connection settings** — base URL, model, format, and agent name are saved on-device for next time (the API key is kept in memory only, never stored)
- ⌨️ **Live typing indicator** — animated dots while the agent is generating a response
- ↺ **Reset conversation** — clear the chat history and start fresh anytime
- ⚠️ **Inline error handling** — failed requests show a clear error bubble instead of breaking the chat
- 🌗 **Light/dark theme aware** — automatically adapts to the system's color scheme
- 📱 **Responsive, mobile-safe layout** — respects safe-area insets for notches and home indicators
- 🎨 **Clean, card-based chat bubbles** with a soft blue/lavender theme

🖥️ Demo

> Add a live demo link here once deployed (e.g. GitHub Pages / Netlify / Vercel)

🛠️ Tech Stack

- **HTML5** — structure/markup
- **CSS3** — styling, layout, responsive design, theming via CSS variables
- **Vanilla JavaScript** — settings management, fetch-based API calls, DOM rendering
- **Fetch API** — communicates directly with the configured AI endpoint (OpenAI or Anthropic format)
- **localStorage** — persists non-sensitive connection settings between sessions

🚀 Getting Started

1. Open the app in your browser
2. Click **⚙ settings**
3. Enter your API's **Base URL**, **API key**, and **model** name
4. (Optional) Give your agent a **name**
5. Choose the correct **format** — OpenAI-compatible or Anthropic
6. Click **Save** and start chatting

🔒 Notes on Security

- The API key is held only in memory for the current session and is never written to disk or `localStorage`
- All other settings (base URL, model, format, agent name) persist locally on your device for convenience
