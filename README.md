<div align="center">
<h1>🛒 grocer</h1>

<p>local store product finder for Claude Code</p>
</div>

---

Claude Code plugin that browses retailer websites via Playwright MCP to build shopping lists with real prices, stock status, and direct links.

## Install

```
/plugin add maferland/grocer
```

## Usage

```
/grocer:search foam tape 20mm, M2 dowel pins, drawer knob
```

## Supported Retailers

| Store | Method | Notes |
|-------|--------|-------|
| Canac | Playwright | French only (`/fr/`) |
| Home Depot | Playwright | Bilingual |
| Canadian Tire | Playwright / Google | Finicky, Google fallback |
| Dollarama | In-store only | No useful website |
| Amazon.ca | Manual browse | Anti-bot protection |

## License

[MIT](LICENSE)
