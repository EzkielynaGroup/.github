## Ezkielyna

An independent AI API gateway: one key for DeepSeek, GLM, Kimi, Qwen, MiniMax, Claude, GPT, Gemini and more, through endpoints compatible with OpenAI and Anthropic. Prepaid API Credit from $0.5, paid with QRIS (DANA, GoPay, OVO, m-banking), USDT or Binance Pay. Billed per token; the balance does not expire.

| | |
|---|---|
| OpenAI format | `https://api.ezkielyna.store/v1` |
| Anthropic format (Claude Code, Anthropic SDK) | `https://api.ezkielyna.store` (no `/v1`) |
| Models and live prices | [ezkielyna.store/models](https://ezkielyna.store/models) · [IDR prices](https://ezkielyna.store/harga-api-ai) |
| Status | [api.ezkielyna.store/status](https://api.ezkielyna.store/status) |
| Guides (Claude Code, Cline, Cursor, OpenCode, n8n, …) | [ezkielyna.store/panduan](https://ezkielyna.store/panduan) |
| Cost per use case | [ezkielyna.store/biaya](https://ezkielyna.store/biaya) |

```bash
curl https://api.ezkielyna.store/v1/chat/completions \
  -H "Authorization: Bearer $EZKIELYNA_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"deepseek-v4.1-flash","messages":[{"role":"user","content":"Halo!"}]}'
```

### Repositories
- [**ezkielyna-api-examples**](https://github.com/EzkielynaGroup/ezkielyna-api-examples): copy-paste examples for curl, Python, Node.js, PHP/Laravel, Google Sheets, Claude Code, OpenCode, Cline, Cursor, Continue, n8n, Dify, Open WebUI and more.
- [**bot-wa-ai-starter**](https://github.com/EzkielynaGroup/bot-wa-ai-starter): open-source AI chatbot starter for Telegram and WhatsApp (Cloud API), in Indonesian, for any OpenAI-compatible API.

### Bahasa Indonesia
Gateway API AI independen: satu API key untuk banyak model AI, kompatibel dengan format OpenAI dan Anthropic. Isi saldo API Credit mulai $0.5 lewat QRIS (DANA, GoPay, OVO, m-banking), USDT atau Binance Pay; dibayar per token dan saldo tidak hangus. Mulai dari [ezkielyna.store/api-credit](https://ezkielyna.store/api-credit), lalu ikuti [panduan pemasangan](https://ezkielyna.store/panduan) untuk alat yang kamu pakai.

<sub>Ezkielyna is not affiliated with the model vendors. Model names belong to their owners.</sub>
