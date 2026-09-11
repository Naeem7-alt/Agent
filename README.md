# Agentic Product for YouTube & Gmail

An intelligent, agentic workflow automation and content management system designed to seamlessly bridge Google Workspace (Gmail) and YouTube content creation, analysis, and communication workflows.

---

## 📂 Project Structure

```text
├── app/
│   ├── __init__.py          # Core application initialization and factory setup
│   ├── gmail/               # Gmail agent package
│   │   ├── __init__.py
│   │   ├── gmail_gen.py     # AI generation module for Gmail responses & content
│   │   └── gmail_write.py   # Gmail API writer/drafting service integration
│   ├── youtube/             # YouTube agent package
│   │   ├── __init__.py
│   │   └── player.py        # YouTube media player control & transcript analysis
│   └── templates/           # Web interface templates
│       └── index.html       # Primary UI dashboard
├── requirements.txt         # Project dependencies
└── wsgi.py                  # WSGI entry point for production deployment
```

---

## ✨ Features

- **Gmail Agent (`app/gmail/`)**:
  - `gmail_gen.py`: Leverages generative AI models to draft contextual email responses, summarize lengthy threads, and organize incoming communications.
  - `gmail_write.py`: Handles secure API operations to automatically send, draft, or label messages via the official Google Workspace APIs.

- **YouTube Agent (`app/youtube/`)**:
  - `player.py`: Integrates YouTube playback capabilities, transcript retrieval, and video context extraction for downstream agent processing.

- **Dashboard UI (`app/templates/index.html`)**:
  - Clean web interface for monitoring agent logs, manually triggering agent runs, and reviewing generated drafts or insights.

---

    
