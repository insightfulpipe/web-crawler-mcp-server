# Web Crawler MCP Server (SEO Crawler) by Insightful Pipe

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/crawler)
[![Insightful Pipe](https://img.shields.io/badge/Insightful_Pipe-MCP_Servers-purple)](https://insightfulpipe.com/mcp-servers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Comprehensive SEO auditing and web crawling through AI with MCP.**

Part of the [Insightful Pipe MCP Server Collection](https://insightfulpipe.com/mcp-servers) — The Web Crawler MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to perform SEO audits, extract data, and analyze websites. Run 25+ specialized SEO checks, generate sitemaps, and extract brand information.

[![Explore All MCP Servers](https://img.shields.io/badge/Explore_All-MCP_Servers-blue?style=for-the-badge)](https://insightfulpipe.com/mcp-servers)

![Web Crawler MCP Server](https://insightfulpipe.com/images/ip-logo.png)

## MCP Server URL

```
https://crawler.insightfulmcp.com/
```

## What is Web Crawler MCP?

Web Crawler MCP is a **remote Model Context Protocol server** that provides AI assistants with comprehensive SEO auditing and web crawling capabilities. This integration allows you to:

- Run 25+ specialized SEO checkers on any URL
- Generate XML sitemaps and robots.txt files
- Extract brand design elements from websites
- Audit technical SEO, content quality, and security
- Analyze mobile responsiveness and page speed

## Installation

### Claude

1. Copy the MCP Server URL: `https://crawler.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://crawler.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add crawler https://crawler.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://crawler.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

### SEO Checkers

| Action | Description |
|--------|-------------|
| `link-extractor` | Extract all links from a page and categorize them (internal and external) |
| `seo-audit-checker` | Comprehensive SEO audit covering technical and content issues |
| `page-speed-checker` | Measure load times and highlight slow resources |
| `content-optimizer-checker` | Analyze on-page content quality and keyword density |
| `internal-linking-checker` | Map internal links and surface opportunities |
| `social-media-checker` | Validate Open Graph and Twitter Card metadata |
| `ssl-certificate-checker` | Inspect certificate chain, expiry, and HTTPS enforcement |
| `llms-txt-checker` | Parse llms.txt instructions for AI crawlers |
| `structured-data-checker` | Validate Schema.org markup and structured data coverage |
| `ai-crawler-checker` | Check permissions for AI training bots and crawlers |
| `mobile-viewport-checker` | Ensure viewport meta tags and responsive meta configs are in place |
| `amp-checker` | Verify AMP implementation quality and discoverability |
| `robots-txt-checker` | Parse robots.txt directives and highlight blocking issues |
| `mobile-responsive-checker` | Audit responsive layout rules and breakpoints |
| `meta-tags-checker` | Inspect meta title/description tags across the page |
| `headings-checker` | Review heading hierarchy (H1-H6) for structure gaps |
| `image-optimization-checker` | Check alt text, formats, and compression levels |
| `link-analysis-checker` | Detect broken or low-quality links on page |
| `indexability-checker` | Review robots/meta directives affecting indexation |
| `canonical-checker` | Validate canonical URLs and conflicting hints |
| `status-code-checker` | Trace HTTP status/redirect chains for a URL |
| `hreflang-checker` | Review international hreflang annotations |
| `security-headers-checker` | Check CSP/HSTS and other security headers |
| `content-quality-checker` | Score readability, word count, and duplication risk |
| `url-structure-checker` | Evaluate keyword usage and cleanliness of URLs |
| `language-checker` | Verify html[lang] attributes and language targeting |
| `page-load-checker` | Measure page weight and render-blocking assets |
| `deprecated-html-checker` | Detect obsolete tags or attributes still in use |
| `favicon-checker` | Confirm favicon/icon discovery across devices |
| `character-encoding-checker` | Validate declared charset and encoding consistency |

### Generators

| Action | Description |
|--------|-------------|
| `sitemap-generator` | Crawl the target domain and produce an XML sitemap |
| `robots-txt-generator` | Generate robots.txt content with optional AI bot restrictions |

### Extractors

| Action | Description |
|--------|-------------|
| `brand-extractor` | Extract brand design details from a website (colors, fonts, buttons, logos) |

## Usage Examples

### Full SEO Audit

```
"Run a comprehensive SEO audit on https://example.com"
```

### Check Technical SEO

```
"Check the robots.txt and indexability of https://mysite.com"
```

### Analyze Internal Links

```
"Map all the internal links on this page"
```

### Generate Sitemap

```
"Generate an XML sitemap for https://example.com"
```

### Extract Brand Elements

```
"Extract the brand colors, fonts, and logos from https://company.com"
```

### Security Audit

```
"Check the SSL certificate and security headers for this site"
```

## Why Web Crawler MCP?

### For SEO Professionals
- **Comprehensive audits** - 25+ specialized checks
- **Technical SEO** - Robots, canonical, structured data
- **Content analysis** - Quality scoring and optimization

### For Web Developers
- **Debug issues** - Find broken links, redirect chains
- **Performance** - Page speed and resource analysis
- **Security** - SSL and header validation

### For Agencies
- **Client audits** - Quick site assessments
- **Competitive analysis** - Analyze competitor sites
- **Reporting** - Generate findings conversationally

## Security & Privacy

- **Secure requests** - HTTPS support
- **Rate limiting** - Respectful crawling
- **Robots.txt compliance** - Respects directives by default
- **User agent** - Identifies crawler appropriately

## Explore More MCP Servers by Insightful Pipe

Visit **[insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)** to discover our full collection of MCP servers for marketing and analytics.

### SEO & Performance MCP Servers
- [PageSpeed MCP](https://insightfulpipe.com/mcp-servers/pagespeed) - Performance analysis
- [Google Search Console MCP](https://insightfulpipe.com/mcp-servers/google-search-console) - Search analytics
- [Screenshot MCP](https://insightfulpipe.com/mcp-servers/screenshot) - Visual capture
- [Google My Business MCP](https://insightfulpipe.com/mcp-servers/google-my-business) - Local SEO

### Analytics MCP Servers
- [Google Analytics MCP](https://insightfulpipe.com/mcp-servers/google-analytics) - Website analytics
- [Enrichment MCP](https://insightfulpipe.com/mcp-servers/enrichment) - Data enrichment

**[View All MCP Servers →](https://insightfulpipe.com/mcp-servers)**

## Resources

- [Documentation](https://insightfulpipe.com/docs/crawler)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **All MCP Servers**: [insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)
- **Email**: support@insightfulpipe.com

---

**[Insightful Pipe](https://insightfulpipe.com)** — AI-powered marketing analytics through MCP servers. [Explore all integrations →](https://insightfulpipe.com/mcp-servers)

## License

MIT License - see [LICENSE](LICENSE) for details.
