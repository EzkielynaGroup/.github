## Ezkielyna

An independent AI API gateway: one key for DeepSeek, GLM, Kimi, Qwen, MiniMax, Claude, GPT, Gemini and more, through endpoints compatible with OpenAI and Anthropic. Prepaid API Credit from $0.5, paid with QRIS (DANA, GoPay, OVO, m-banking), USDT or Binance Pay. Billed per token; the balance does not expire.

| | |
|---|---|
| OpenAI format | `https://api.ezkielyna.store/v1` |
| Anthropic format (Claude Code, Anthropic SDK) | `https://api.ezkielyna.store` (no `/v1`) |
| Models and live prices | [ezkielyna.store/models](https://ezkielyna.store/models?utm_source=github&utm_medium=org-profile) · [IDR prices](https://ezkielyna.store/harga-api-ai?utm_source=github&utm_medium=org-profile) |
| Status and usage ranking | [api.ezkielyna.store/status](https://api.ezkielyna.store/status) · [ezkielyna.store/peringkat](https://ezkielyna.store/peringkat?utm_source=github&utm_medium=org-profile) |
| Guides (Claude Code, Cline, Cursor, OpenCode, n8n, …) | [ezkielyna.store/panduan](https://ezkielyna.store/panduan?utm_source=github&utm_medium=org-profile) |
| Cost per use case | [ezkielyna.store/biaya](https://ezkielyna.store/biaya?utm_source=github&utm_medium=org-profile) |

```bash
curl https://api.ezkielyna.store/v1/chat/completions \
  -H "Authorization: Bearer $EZKIELYNA_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"deepseek-v4.1-flash","messages":[{"role":"user","content":"Halo!"}]}'
```

### MCP servers
Single-file Node.js servers for Claude Desktop, Claude Code, Cursor and OpenCode. Install with `npx -y <name>`; all are in the [MCP Registry](https://registry.modelcontextprotocol.io).

**No API key needed (open data, offline tools)**

| Server | What it does |
|---|---|
| [mcp-bmkg](https://github.com/EzkielynaGroup/mcp-bmkg) | Latest earthquakes and village-level weather forecasts from BMKG open data |
| [mcp-wilayah-indonesia](https://github.com/EzkielynaGroup/mcp-wilayah-indonesia) | Indonesian regions from provinsi to desa/kelurahan with Kemendagri codes (pairs with mcp-bmkg) |
| [mcp-hari-libur-indonesia](https://github.com/EzkielynaGroup/mcp-hari-libur-indonesia) | Public holidays and cuti bersama (SKB 3 Menteri) plus working-day math |
| [mcp-rupiah](https://github.com/EzkielynaGroup/mcp-rupiah) | Terbilang, Rupiah formatting and parsing, PPN calculator |
| [mcp-qris](https://github.com/EzkielynaGroup/mcp-qris) | Parse and validate QRIS, add an amount, render SVG (offline, never moves money) |
| [ai-model-status-mcp](https://github.com/EzkielynaGroup/ai-model-status-mcp) | Which AI models are up, fast, popular or low-priced right now |

**With an Ezkielyna API key**

| Server | What it does |
|---|---|
| [ezkielyna-mcp](https://github.com/EzkielynaGroup/ezkielyna-mcp) | Ask or compare other AI models for a second opinion, web search, balance |
| [ezkielyna-image-mcp](https://github.com/EzkielynaGroup/ezkielyna-image-mcp) | Create and edit images from local files |
| [ezkielyna-audio-mcp](https://github.com/EzkielynaGroup/ezkielyna-audio-mcp) | Text to speech and transcription (Indonesian too) |

### Starters, guides and data
- [**ezkielyna-api-examples**](https://github.com/EzkielynaGroup/ezkielyna-api-examples): copy-paste examples for curl, Python, Node.js, PHP/Laravel, Google Sheets, Claude Code, OpenCode, Cline, Cursor, Continue, n8n, Dify, Open WebUI and more.
- [**ezkielyna-agent**](https://github.com/EzkielynaGroup/ezkielyna-agent): open-source AI coding agent (CLI/TUI + desktop).
- [**bot-wa-ai-starter**](https://github.com/EzkielynaGroup/bot-wa-ai-starter): AI chatbot starter for Telegram and WhatsApp (Cloud API), in Indonesian.
- [**n8n-workflows-indonesia**](https://github.com/EzkielynaGroup/n8n-workflows-indonesia): ready-to-import n8n workflows for small businesses.
- [**prompt-umkm-indonesia**](https://github.com/EzkielynaGroup/prompt-umkm-indonesia): 45 copy-ready Indonesian prompts for sales, customer service, content, operations and code.
- [**tips-ai-indonesia**](https://github.com/EzkielynaGroup/tips-ai-indonesia): practical AI tips for Indonesian developers and small businesses.
- [**ai-api-usage-data-indonesia**](https://github.com/EzkielynaGroup/ai-api-usage-data-indonesia): daily open data (CC BY 4.0) on model usage, uptime, latency and list prices.
- [**awesome-ai-indonesia**](https://github.com/EzkielynaGroup/awesome-ai-indonesia) and [**awesome-mcp-indonesia**](https://github.com/EzkielynaGroup/awesome-mcp-indonesia): curated lists of Indonesian AI resources and MCP servers.

### Bahasa Indonesia
Gateway API AI independen: satu API key untuk banyak model AI, kompatibel dengan format OpenAI dan Anthropic. Isi saldo API Credit mulai $0.5 lewat QRIS (DANA, GoPay, OVO, m-banking), USDT atau Binance Pay; dibayar per token dan saldo tidak hangus. Mulai dari [ezkielyna.store/api-credit](https://ezkielyna.store/api-credit?utm_source=github&utm_medium=org-profile), lalu ikuti [panduan pemasangan](https://ezkielyna.store/panduan?utm_source=github&utm_medium=org-profile) untuk alat yang kamu pakai.

Server MCP di atas bisa dipasang di Claude Desktop, Claude Code, Cursor, atau OpenCode dengan `npx -y <nama>`. Enam di antaranya (BMKG, wilayah, hari libur, Rupiah, QRIS, status model) gratis dan tidak butuh API key. Punya ide atau menemukan bug? Buka issue di repo terkait.

<sub>Ezkielyna is not affiliated with the model vendors. Model names belong to their owners.</sub>
