# MCPFinder

> Curated, searchable directory of MCP (Model Context Protocol) servers.

**Live:** https://mcpfinder.vercel.app

## Features

- Search 20+ curated MCP servers
- Filter by category: Dev Tools, Databases, Productivity, Browser, AI Infra...
- One-click copy of install commands (`npx`, `uvx`)
- Star counts, language badges, official server tags
- Dark theme, mobile responsive, zero dependencies

## How it works

Pure static HTML/JS. Servers defined in `data/servers.json`. No build step.

## Add a server

Open a PR editing `data/servers.json` with:
- `name`, `description`, `category`, `tags`, `author`
- `official` (true/false), `stars`, `language`, `license`
- `repo`, `install`, `inspect` (npx @modelcontextprotocol/inspector ... cmd)

## Categories

`dev-tools` · `databases` · `productivity` · `browser` · `ai-infra` · `search` · `payments` · `location`

## Tech

- Vanilla HTML/CSS/JS
- Tailwind CSS (CDN)
- Vercel (static hosting)

## License

MIT
