---
description: Teach the grocer about a new store — URL patterns, search tips, gotchas
argument-hint: <store name or URL>
---

The user wants to teach the grocer about a store. Use Playwright MCP to explore the store's website and figure out:

1. **Search URL pattern** — how search queries map to URLs
2. **Language** — French-only, English-only, or bilingual
3. **JS-rendered?** — does WebFetch work or is Playwright required?
4. **Product page structure** — where are name, price, stock, product code?
5. **Gotchas** — redirects, anti-bot, search quirks

Arguments: $ARGUMENTS

Write the store profile to `~/dev/grocer/config/stores/{store-name}.md` with:

```markdown
# Store Name

- **URL:** https://...
- **Search:** `https://store.com/search?q=TERMS`
- **Language:** French / English / Bilingual
- **Requires Playwright:** yes/no
- **Gotchas:** any quirks discovered

## Tips
- keyword strategies that work well
- anything learned from browsing the site
```

Then update `~/dev/grocer/config/preferences.md` to add this store to the known stores list.
