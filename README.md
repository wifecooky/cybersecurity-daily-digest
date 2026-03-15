# Security Daily Digest

Automated, trilingual daily digest for cybersecurity professionals.

Collects articles from 17 sources — Krebs on Security, Bruce Schneier, Google TAG, vendor security blogs, and Hacker News — then uses AI to score, filter, and translate into English, Chinese, and Japanese.

Built with [digest-factory](https://github.com/wifecooky/digest-factory).

## Sources

| Category | Sources |
|----------|---------|
| Research | Krebs on Security, Bruce Schneier, The Hacker News |
| Media | BleepingComputer, Dark Reading, Wired Security, Ars Technica Security, Daily Swig, Risky Biz |
| Vendors | Google TAG, Google Security Blog, Microsoft Security, GitHub Security, Cloudflare Security |
| News | Google News Security (en/zh/ja), Hacker News |

## Quick Start

```bash
npm install
cd frontend && npm install && cd ..
export OPENAI_API_KEY=sk-...
npm run generate-daily
cd frontend && npm run build && npm run preview
```

## Pipeline

| Command | Description |
|---------|-------------|
| `npm run collect` | Fetch articles from all sources |
| `npm run filter` | AI editorial selection (security-focused) |
| `npm run translate` | Translate to en/zh/ja |
| `npm run generate-daily` | Full pipeline |
| `npm run newsletter` | Send via Buttondown |

## Contact

[@wifecooky](https://x.com/wifecooky)
