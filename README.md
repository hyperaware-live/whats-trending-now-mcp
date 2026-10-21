<div align="center">

<a href="https://hyperaware.live/?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp"><img src="https://hyperaware.live/brand/hyperaware.live/logo.png" width="80" height="80" alt="Hyperaware logo"></a>

# Hyperaware: what's trending now, live

What's happening today, in one place. Live trending-now boards for 22 feeds, from Google Trends and TikTok to YouTube, Reddit, X and Amazon, with what moved since yesterday. Read it on the web, or ask your AI through MCP.

[![Free plan](https://img.shields.io/badge/Free-100%20requests/month-2ea44f?style=for-the-badge)](https://hyperaware.live/pricing?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)
[![MCP](https://img.shields.io/badge/MCP-remote%2C%20OAuth-6E56CF?style=for-the-badge)](https://hyperaware.live/docs?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)
[![License: MIT](https://img.shields.io/badge/License-MIT-555555?style=for-the-badge)](LICENSE)

**[Website](https://hyperaware.live/?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)** · **[Get started free](https://hyperaware.live/account?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)** · [Docs](https://hyperaware.live/docs?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) · [Pricing](https://hyperaware.live/pricing?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) · [Live board](https://hyperaware.live/?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)

</div>

```
You: What's happening today across Google, YouTube and Steam?

Claude: (calls get_top_trends for "Google Trends", "YouTube Trending", "Steam Most Played")
        Number one on each board right now, with how far each item moved since yesterday...
```

## Connect in 10 seconds

Pick your app. Every button opens it with Hyperaware already filled in. Claude and ChatGPT sign you in with your Hyperaware account, so there is no API key to copy.

<p align="center">
  <a href="https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=Hyperaware&connectorUrl=https%3A%2F%2Fhyperaware.live%2Fmcp"><img src="https://img.shields.io/badge/Add%20to-Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Add to Claude"></a>
  <a href="https://chatgpt.com/plugins#settings/Connectors?create-connector=true&redirectAfter=%2Fplugins"><img src="https://img.shields.io/badge/Add%20to-ChatGPT-10A37F?style=for-the-badge&logo=openai&logoColor=white" alt="Add to ChatGPT"></a>
  <a href="https://cursor.com/en/install-mcp?name=hyperaware&config=eyJ1cmwiOiAiaHR0cHM6Ly9oeXBlcmF3YXJlLmxpdmUvbWNwIn0%3D"><img src="https://img.shields.io/badge/Add%20to-Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white" alt="Add to Cursor"></a>
  <a href="https://insiders.vscode.dev/redirect/mcp/install?name=hyperaware&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A//hyperaware.live/mcp%22%7D"><img src="https://img.shields.io/badge/Add%20to-VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Add to VS Code"></a>
</p>

| App | After you click |
|---|---|
| **Claude** | The connector name and URL are prefilled. Confirm, sign in to Hyperaware, approve access. |
| **ChatGPT** | Turn on Developer mode under Settings → Security and login. Name it `Hyperaware`, URL `https://hyperaware.live/mcp`, choose OAuth, sign in. |
| **Cursor** | Approve the install. Sign in to Hyperaware when Cursor asks. |
| **VS Code** | Approve the install. Open Chat in Agent mode and enable the Hyperaware tools. |

**Server URL:** `https://hyperaware.live/mcp`

**Every coding agent at once** (Cursor, Claude Code, VS Code, Windsurf and more, detected automatically):

```bash
npx add-mcp https://hyperaware.live/mcp
```

Then ask: `Using Hyperaware, what's trending on Google right now?`

<details>
<summary><b>Claude Code</b></summary>

```bash
claude mcp add --transport http hyperaware https://hyperaware.live/mcp
```

</details>

<details>
<summary><b>Grok</b></summary>

In Grok, open Connectors, choose **New Connector**, then **Custom**, and paste `https://hyperaware.live/mcp`. Sign in to Hyperaware when asked. Menu names can differ slightly per plan.

</details>

<details>
<summary><b>Use an API key instead</b> (Claude Desktop, Windsurf, Cline, any client)</summary>

[Get a free key](https://hyperaware.live/account?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp). Your key is shown on the page and emailed to you. In your app, add a remote MCP server:

```json
{
  "mcpServers": {
    "hyperaware": {
      "url": "https://api.hyperaware.live/mcp",
      "headers": {
        "Authorization": "Bearer YOUR_API_KEY"
      }
    }
  }
}
```

Signed in, the account page also has Cursor and VS Code buttons with your key already included: [hyperaware.live/account](https://hyperaware.live/account?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp).

</details>

Full setup for every app: [hyperaware.live/docs](https://hyperaware.live/docs?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp).

## What you can ask

- What's happening today across Google, TikTok and YouTube?
- What's trending now on X and Reddit?
- Which TikTok searches climbed the most since yesterday?
- What are the top Amazon best sellers today?
- Which games are most played on Steam right now?

Tip: start with "Using Hyperaware" so your AI uses these tools instead of a web search.

## 22 live feeds

Each feed has a standing page that always shows the current ranking.

| Feed | Category | Page |
|---|---|---|
| Google Trends | Search | [hyperaware.live/whats-trending/google-trends](https://hyperaware.live/whats-trending/google-trends?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Google News | News | [hyperaware.live/whats-trending/google-news](https://hyperaware.live/whats-trending/google-news?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| TikTok Trending Searches | Social | [hyperaware.live/whats-trending/tiktok-searches](https://hyperaware.live/whats-trending/tiktok-searches?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| TikTok Shop | Shopping | [hyperaware.live/whats-trending/tiktok-shop](https://hyperaware.live/whats-trending/tiktok-shop?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| YouTube Trending | Social | [hyperaware.live/whats-trending/youtube](https://hyperaware.live/whats-trending/youtube?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| X (Twitter) Trending | Social | [hyperaware.live/whats-trending/x](https://hyperaware.live/whats-trending/x?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Reddit Hot Posts | Social | [hyperaware.live/whats-trending/reddit](https://hyperaware.live/whats-trending/reddit?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Reddit World News | News | [hyperaware.live/whats-trending/reddit-news](https://hyperaware.live/whats-trending/reddit-news?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Wikipedia Trending | Search | [hyperaware.live/whats-trending/wikipedia](https://hyperaware.live/whats-trending/wikipedia?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Amazon Best Sellers | Shopping | [hyperaware.live/whats-trending/amazon](https://hyperaware.live/whats-trending/amazon?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Amazon by Category | Shopping | [hyperaware.live/whats-trending/amazon-category](https://hyperaware.live/whats-trending/amazon-category?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| App Store Top Free | Apps | [hyperaware.live/whats-trending/app-store-free](https://hyperaware.live/whats-trending/app-store-free?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| App Store Top Paid | Apps | [hyperaware.live/whats-trending/app-store-paid](https://hyperaware.live/whats-trending/app-store-paid?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Google Play | Apps | [hyperaware.live/whats-trending/google-play](https://hyperaware.live/whats-trending/google-play?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Top Websites | Web | [hyperaware.live/whats-trending/websites](https://hyperaware.live/whats-trending/websites?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Spotify Top Podcasts | Media | [hyperaware.live/whats-trending/spotify](https://hyperaware.live/whats-trending/spotify?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Steam Most Played | Media | [hyperaware.live/whats-trending/steam](https://hyperaware.live/whats-trending/steam?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| IMDb MOVIEmeter | Media | [hyperaware.live/whats-trending/imdb](https://hyperaware.live/whats-trending/imdb?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Open Library Trending Books | Media | [hyperaware.live/whats-trending/books](https://hyperaware.live/whats-trending/books?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| GitHub Trending | Developer | [hyperaware.live/whats-trending/github](https://hyperaware.live/whats-trending/github?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Substack | News | [hyperaware.live/whats-trending/substack](https://hyperaware.live/whats-trending/substack?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |
| Substack by Category | News | [hyperaware.live/whats-trending/substack-category](https://hyperaware.live/whats-trending/substack-category?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp) |

| | Free board | Pro |
|---|---|---|
| Depth | Top 10 per feed | Full ranking |
| Freshness | About 24 hours behind | Live |
| History | Daily archive | Full history |

## Tools

Three read-only tools. Your AI picks the right one from your question.

| Tool | Use when | Needs a keyword? |
|---|---|---|
| `get_top_trends` | What is ranking on a platform right now | No |
| `get_growth` | Percent change over 7D to 5Y, several windows and sources in one call | Yes |
| `get_time_series` | Up to 5 years of history for one keyword on one source | Yes |

## Free and paid

| Plan | Requests a month | Price |
|---|---|---|
| Free | 100 | $0 |
| Starter | 1,000 | $19 / month |
| Pro | 5,000 | $49 / month |
| Business | 25,000 | $199 / month |

Every plan has every source. Annual billing saves 20%. Only successful calls count. [Get started free](https://hyperaware.live/account?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp): email and an 8-digit code, no password, no credit card.

## FAQ

**What is happening today?**  
The board at [hyperaware.live](https://hyperaware.live/) shows the top items on 22 feeds side by side: Google Trends, Google News, TikTok, YouTube, X, Reddit, Wikipedia, Amazon, app stores, Spotify, Steam, IMDb, GitHub and more.

**What's trending right now?**  
Open the feed you care about below. Each one has a standing page that always shows the current ranking.

**Is it free?**  
The public board is free: the top 10 per feed, about 24 hours behind. Pro is the live full board with history. MCP and API use the same free key, with 100 requests a month.

**Can my AI read the board?**  
Yes. Connect the MCP server above and ask in plain language. Claude, ChatGPT, Cursor and VS Code all work.

## Links

- Website: [hyperaware.live](https://hyperaware.live/?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)
- Get started free: [hyperaware.live/account](https://hyperaware.live/account?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)
- Docs and setup for every app: [hyperaware.live/docs](https://hyperaware.live/docs?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)
- Pricing: [hyperaware.live/pricing](https://hyperaware.live/pricing?utm_source=github&utm_medium=readme&utm_campaign=whats-trending-now-mcp)
- For AI agents: [hyperaware.live/llms.txt](https://hyperaware.live/llms.txt)
- Support: hello@hyperaware.live

## License

MIT for the contents of this repository. Use of the hosted service follows the [terms of service](https://hyperaware.live/terms).
