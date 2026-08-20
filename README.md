# AI Automation Portfolio

A case-study portfolio site showcasing AI chatbot and workflow automation projects — built to demonstrate real, working automations rather than just describe them.

🔗 **Live site:** [atrubaautomates.github.io/portfolioo](https://atrubaautomates.github.io/portfolioo/)

## What's Inside

- **Hero** — intro and quick pitch
- **My Work** — case studies with live chatbot demos:
  - Bella's Pizzeria — restaurant FAQ + table booking chatbot
  - SmileCare Dental — appointment booking chatbot
  - Elite Properties — real estate lead qualification chatbot
- **About Me** — background and focus area

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Automation backend:** [n8n](https://n8n.io) (webhook-triggered chat workflows)
- **Hosting:** GitHub Pages

## How It Works

Each case study links to a live chat widget wired to its own n8n webhook. The chatbots handle FAQs, booking requests, and lead qualification using Google Sheets as the data source.

## Running Locally

This is a static site — just open `index.html` in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 8000
```

---
Built by [Atrooba Batool](https://github.com/atrubaautomates) · [LinkedIn](https://www.linkedin.com/in/atrooba-batool/)
