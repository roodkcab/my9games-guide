---
title: "Use my9games with Claude or ChatGPT (MCP connector)"
description: Add https://my9games.cc/mcp as a custom connector in Claude or ChatGPT, then ask for a my 9 games grid or tier list in plain words. Prompts and tools inside.
permalink: /use-with-ai/
---

my9games.cc runs a public **MCP server** (Model Context Protocol). Add it to Claude or ChatGPT as a connector and the assistant can search the game catalog, build a grid or a tier list, and hand you the finished image with a share link, without you opening the site.

Connector URL:

```
https://my9games.cc/mcp
```

It is free and needs no account, API key or sign-in.

## Add it to Claude

1. In Claude (web or desktop), open **Settings → Connectors**.
2. Choose **Add custom connector**.
3. Name: `My9Games`. Remote MCP server URL: `https://my9games.cc/mcp`.
4. Leave the advanced / OAuth fields empty and press **Add**.
5. In a new chat, check that My9Games is switched on in the tools menu, then ask away.

## Add it to ChatGPT

1. Open **Settings → Apps & Connectors** (on some plans you first enable **Developer mode** under Advanced settings to add your own connector).
2. Choose **Create** (or **Add custom connector**).
3. Name: `My9Games`. MCP server URL: `https://my9games.cc/mcp`.
4. For authentication pick **No authentication**. **Leave "Requires sign-in" off**: the server has no login, so there is nothing to sign in to.
5. Save, then pick the connector from the **+** menu in a chat.

Menu names change from time to time; if yours differ, look for "connectors", "apps" or "MCP" in the settings.

## Things to ask

- "Make my 9 games grid: Breath of the Wild, Final Fantasy VII, Melee, Hollow Knight, Elden Ring, Portal 2, Hades, Stardew Valley and Red Dead 2."
- "Guess my nine favorite games from this conversation, then compare them with my real list."
- "A tier list of every mainline Zelda game, S to C."
- "Rank every Soulsborne game with tiers named Peak, Great, Fine and Never again."
- "Import my Steam library (steamcommunity.com/id/yourname) and make a borderless grid of my 20 most played games with hours."
- "Now do 10–16: add seven more to my grid."

The assistant replies with the image, a share link that opens the result on my9games.cc (where you can keep editing), and one-click **Post on X** / **Post on Reddit** links.

![A tier list made through the connector: "Every Zelda game, ranked"]({{ '/assets/img/example-mcp-zelda-tier.jpg' | relative_url }}){: width="900" height="653" loading="lazy"}

## The tools

| Tool | What it does |
|---|---|
| `search_games` | Finds a game in the 60,000+ game catalog. Understands acronyms, nicknames and years, one game per call. |
| `create_grid` | Draws a grid from 9 up to 25 games, classic or borderless, optionally with hours. Returns the image, a share link and post links. |
| `create_tier_list` | Draws a tier list: up to 8 tiers with any names and colors, up to 100 games. Returns the image and a link that opens the list in the tier list maker. |
| `compare_grids` | Scores a guessed grid against your real picks (matches, exact positions, a 0–100 score). Handy for "guess my nine" games. |
| `import_steam_library` | Reads a public Steam library and returns your most played games with hours. Your Game details must be public ([how](../steam-import/)). Nothing about the account is stored. |

## Tips

- If a cover is the wrong release, say which one: "the 2023 Resident Evil 4", "the original Final Fantasy VII, not the remake".
- Prefer to do it yourself? Every share link opens in the [grid maker](https://my9games.cc/) or [tier list maker](https://my9games.cc/tier), so you can let the AI draft and finish by hand.

**[Or make it yourself on my9games.cc →](https://my9games.cc/)**
