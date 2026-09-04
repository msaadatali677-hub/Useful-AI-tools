# 🤖 AI Tools Directory

A single-page, searchable directory of useful AI tools — organized into 12 categories covering chatbots, coding, writing, design, video, audio, data, automation, and more. Built as a clean, dark-themed static website with live search.

**🔗 Live demo:** _add your deployed link here
https://useful-ai-tools-puce.vercel.app/

## ✨ Features

- **70+ AI tools** across 12 real-world categories
- **Live search** — instantly filter tools by name as you type
- **Clickable links** — every tool opens its official website in a new tab
- **Responsive layout** — works on desktop, tablet, and mobile
- **No frameworks, no build step** — pure HTML, CSS, and vanilla JavaScript
- **Dark, minimal design** with Space Grotesk + Inter typography

## 📂 Categories

| Category | Examples |
|---|---|
| 🧠 AI Chatbots & General AI | ChatGPT, Claude, Gemini, Copilot, Grok, DeepSeek |
| 🔎 Research & Learning | Perplexity, NotebookLM, Elicit, Consensus, Scite, Wolfram Alpha |
| 💻 Coding & Development | GitHub Copilot, Cursor, Replit, Windsurf, Lovable, v0, Bolt.new |
| ✍️ Writing & Content | Grammarly, Jasper, Copy.ai, Writesonic, QuillBot, Notion AI |
| 🎨 Image Generation & Design | Midjourney, Adobe Firefly, Canva, Ideogram, Leonardo AI, Recraft |
| 🎬 Video Creation & Editing | Runway, HeyGen, Synthesia, Descript, CapCut, VEED, Kling AI |
| 🎙️ Voice & Audio | ElevenLabs, Murf, Adobe Podcast, Suno, Udio, Otter.ai |
| 📊 Data Analysis & BI | Julius AI, Rows, Akkio, Power BI Copilot, Tableau AI |
| 📑 Documents & Presentations | Gamma, Beautiful.ai, Tome, ChatPDF, Humata |
| ⚙️ Automation & Workflows | Zapier, Make, n8n, Power Automate, Relevance AI |
| 🧑‍💼 Meetings & Productivity | Fireflies.ai, Fathom, Avoma, Granola |
| 🤖 AI Agents & Development | Manus, CrewAI, LangChain, LlamaIndex, OpenAI API, Anthropic API |

## 🚀 Getting Started

No installation or dependencies required.

1. Clone the repository
   ```bash
   git clone https://github.com/msaadatali677-hub/ai-tools-directory.git
   cd ai-tools-directory
   ```
2. Open `index.html` directly in your browser, **or** serve it locally:
   ```bash
   npx serve .
   ```

## 🛠️ Built With

- HTML5
- CSS3 (custom properties, CSS Grid, Flexbox)
- Vanilla JavaScript (no libraries or frameworks)
- [Google Fonts](https://fonts.google.com/) — Space Grotesk & Inter

## 📁 Project Structure

```
ai-tools-directory/
├── index.html      # Everything — markup, styles, and script in one file
└── README.md
```

## 🙋 Adding a New Tool

Open `index.html` and find the `data` array in the `<script>` section. Each category is an object with an `icon`, a `title`, and a `tools` array of `[name, url]` pairs:

```js
{
  icon: "🧠",
  title: "AI Chatbots & General AI",
  tools: [
    ["ChatGPT", "https://chat.openai.com"],
    // add a new tool here
    ["NewTool", "https://newtool.com"],
  ]
}
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Saadat Ali** — [CodeWithSaadat](https://codewithsaadat.netlify.app/)

- Portfolio: [codewithsaadat.netlify.app](https://codewithsaadat.netlify.app/)
- LinkedIn: [linkedin.com/in/saadat-ali-3021ab3a5](https://www.linkedin.com/in/saadat-ali-3021ab3a5/)
- GitHub: [@msaadatali677-hub](https://github.com/msaadatali677-hub)

---

⭐️ If you found this useful, consider giving the repo a star!
