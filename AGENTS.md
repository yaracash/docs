> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- The product is **Yara** (always capitalized, never "YARA"). Do not use "Daya" in docs.
- Products: **Wallets as a Service** (WAAS, available now), **Ramps**, **USD Virtual Accounts**, **Yara Liquidity** (the last three are Coming Soon).
- Use "wallet", "deposit", "transfer"/"payout", "whitelisted destination", "API key".
- The external WAAS API authenticates with the `x-yara-api-key` header; base URL `https://api.yara.cash/v1`.
- Whitelisting payout destinations happens in the **dashboard** (`dashboard.yara.cash`), not the API.

## Brand

- Warm, minimal palette: primary brown `#665656`, ink `#211E1D` / `#1C1A19`, cream `#F8F4EF`.
- Font: **Instrument Sans** (set in `docs.json` `fonts.family`).
- Logo + favicon use the Yara "sun/ellipse" mark in `logo/` and `favicon.svg`.

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Keep pages short; split long topics into sub-pages rather than one long page
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
