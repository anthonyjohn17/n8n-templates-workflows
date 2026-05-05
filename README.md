# n8n Templates & Workflows — Portfolio Library

[![Maintainer — anthonyjohn17](https://img.shields.io/badge/maintainer-anthonyjohn17-181717?logo=github)](https://github.com/anthonyjohn17)
[![n8n](https://img.shields.io/badge/automation-n8n-EA4B71)](https://n8n.io/)

A single workspace that brings together **thousands of import-ready [n8n](https://n8n.io/) workflows**, organized for discovery, demos, and client-ready automation ideas. Everything here is curated and published as part of **[John Anthony (@anthonyjohn17)](https://github.com/anthonyjohn17)**’s portfolio—not as a drop-in endorsement of every third-party snippet inside each JSON file.

---

## What’s inside

| Directory | Role |
|-----------|------|
| [`n8n-workflows/`](./n8n-workflows/) | Large **indexed collection** (~2k+ workflows), Python or **Node.js** doc server with **SQLite FTS** search, categories, Mermaid diagrams, Docker-friendly layout. Start here if you want a **browsable library + API**. |
| [`n8n-master-workflows/`](./n8n-master-workflows/) | Templates aimed at **n8n Master** (browser extension)—grouped by business area (Finance, Marketing, Telegram, Gmail, …). Great for quick “browse by scenario.” |
| [`n8n-templates/`](./n8n-templates/) | Older **department / integration** taxonomy (tables in README, category folders like `Telegram/`, `Gmail_and_Email_Automation/`). |
| [`n8n-templates-02/`](./n8n-templates-02/) | **Topic-based** bundles (Healthcare, IoT, DevOps, Legal Tech, …) with per-topic README stubs. |

Workflows overlap across folders; keeping multiple trees preserves different **navigation styles** (search UI vs Chrome extension vs categorical READMEs).

---

## Quick start (browse the big collection)

The richest experience is under `n8n-workflows/`:

```bash
cd n8n-workflows
python -m pip install -r requirements.txt
python run.py
# UI: http://localhost:8000 (see n8n-workflows/README.md for flags like --reindex)
```

**Node.js variant:** see [`n8n-workflows/README-nodejs.md`](./n8n-workflows/README-nodejs.md) (`npm install`, `npm run init`, `npm run index`, `npm start`).

**Docker:** [`n8n-workflows/docker-compose.yml`](./n8n-workflows/docker-compose.yml) and shell helpers in that folder.

To use any template standalone: **n8n → Workflows → Import from file** → pick a JSON under the folder that fits your scenario.

---

## Attribution, licensing, and your responsibility

- **Portfolio maintainer:** [https://github.com/anthonyjohn17](https://github.com/anthonyjohn17)  
- **Provenance:** These files were aggregated from community templates, public repos, educational packs, and similar sources. Original authors remain responsible for their own claims, integrations, rate limits, and terms of service (**OpenAI**, **CoinMarketCap**, **Binance APIs**, SaaS connectors, etc.).  
- **Not legal advice:** Sticky notes / comments inside workflows may contain **outdated branded text** or assertions that were rewritten to point at this portfolio for contact only—they do **not** transfer intellectual property rights. **Review and comply with applicable licenses and vendor terms before production.**  
- **Secrets:** Rotate any API keys, webhooks, or email domains you find in demos; many files still contain **`example.com` placeholders** or generic labels after sanitization—treat everything as **non-production defaults**.

---

## GitHub housekeeping

Clone (after you publish this tree under your account):

```bash
git clone https://github.com/anthonyjohn17/n8n-templates-workflows.git
cd n8n-templates-workflows
```

Keep subfolders as-is when you clone or fork so paths in this README stay valid.

To push an existing local clone (create the empty repo on GitHub first, then):

```bash
git remote add origin https://github.com/anthonyjohn17/n8n-templates-workflows.git
git branch -M main   # optional, if your default branch should be main
git push -u origin main
```

---

## Connect

**[github.com/anthonyjohn17](https://github.com/anthonyjohn17)** · Also on the web at [jaapp.io](https://jaapp.io) (from your public profile).

If this library saved you time, starring the repo when it’s public helps surface it for other builders.
