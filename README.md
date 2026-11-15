# Discond for Cursor

Search live discounts at UAE restaurants, cafés, spas and shops from Cursor's agent.
Discond brings together Fazaa, The Entertainer, Talabat, Careem, Privilee, Smiles,
bank and card offers and more.

This plugin adds the Discond MCP server (`https://mcp.discond.ae/mcp`, read-only).

- Searching works without an account.
- Full offer details and redeem links need a free Discond account. Cursor opens
  Discond sign-in (Google) the first time you ask for one. Disconnect any time in
  Account → Connected apps on www.discond.ae.

Example prompts:

1. Find sushi places with discounts near Dubai Marina, nearest first.
2. Which discount programmes work at YO! Sushi, and which gives the most off?
3. Show me the redeem link for the best deal at Hako Sushi.

Manual setup without the plugin:

```json
{ "mcpServers": { "discond": { "url": "https://mcp.discond.ae/mcp" } } }
```

Docs: https://www.discond.ae/en-us/developers ·
Privacy: https://www.discond.ae/en-us/privacy ·
Terms: https://www.discond.ae/en-us/terms ·
Support: support@discond.ae
