---
name: leafengines
version: 1.2.1
description: LeafEngines - Agricultural Intelligence with Free Tier & Metered Pricing. 1,092+ downloads. 3 tools for soil analysis, crop recommendations, and TurboQuant capabilities. Free tier available with x-free-tier header.
homepage: https://app.soilsidekickpro.com/mcp
source: https://github.com/QWarranto/leafengines-claude-mcp
metadata: {"openclaw":{"emoji":"🌱","os":["darwin","linux"],"requires":{"bins":[]},"install":[{"id":"claude-desktop","kind":"manual","steps":["1. Open Claude Desktop settings","2. Navigate to Developer → MCP Servers","3. Add new server with URL: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server","4. Add header: x-free-tier: true (FREE) OR x-api-key: YOUR_PAID_KEY (Paid)"],"label":"Configure in Claude Desktop"},{"id":"openclaw-mcp","kind":"manual","steps":["1. Choose FREE tier (x-free-tier: true) or PAID tier (get API key from Stripe checkout)","2. Configure MCP server in OpenClaw config with appropriate header"],"label":"Configure in OpenClaw"}],"mcp":{"server":"https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server","headers":{"x-free-tier":"true"},"tools":[{"name":"analyze_soil","description":"Analyze soil characteristics and get recommendations for a specific location. Requires county_fips parameter (5-digit code).","inputSchema":{"type":"object","properties":{"county_fips":{"type":"string","description":"5-digit county FIPS code (e.g., '13067' for Fulton County, GA)"},"api_key":{"type":"string","description":"Optional API key for paid features (use x-api-key header instead)"}},"required":["county_fips"]}},{"name":"recommend_crop","description":"Get crop recommendations based on soil analysis.","inputSchema":{"type":"object","properties":{"county_fips":{"type":"string","description":"5-digit county FIPS code"},"api_key":{"type":"string","description":"Optional API key for paid features"}},"required":["county_fips"]}},{"name":"check_turboquant","description":"Check if TurboQuant capabilities are available for a location (FREE). No authentication required.","inputSchema":{"type":"object","properties":{"county_fips":{"type":"string","description":"5-digit county FIPS code"}},"required":["county_fips"]}}]}}}
---

# LeafEngines MCP Server v1.2.1

**Agricultural Intelligence with Free Tier & Metered Pricing** for Claude and OpenClaw. **1,092+ downloads** since March 29.

## ⚡ Get Started Now

**Free tier — no signup, no credit card:**
- **Test key:** `leaf-test-370df0a2e62e` (works immediately)
- **Free header:** `x-free-tier: true` (no key needed)

**Ready for production?**
- [Starter — $149/mo →](https://buy.stripe.com/5kQ6oHcB88bR93s8MSaMU04)
- [Pro — $499/mo →](https://buy.stripe.com/14A6oH7gO3VBcfE1kqaMU05)

**Partner Program:** Stop building for free. Use our API to sell $100–200 soil reports to local farmers, drone pilots, and GIS communities. You buy each report for $25. [Join our Partner Program →](https://soilcertify.com)

## 🌾 What It Does

**3 Agricultural Intelligence Tools:**
1. **Analyze Soil** — Soil characteristics and recommendations (requires `county_fips`)
2. **Recommend Crop** — Crop suggestions based on soil analysis
3. **Check TurboQuant** — Hardware optimization check (FREE, always, no auth)

**Why 1,092+ Developers Choose Us:**
- ✅ **Free tier available** — No API key required for testing
- ✅ **Metered pricing** — Credit packs + monthly subscriptions from $149/mo
- ✅ **Simple integration** — 3 focused tools with clear parameters
- ✅ **Proven adoption** — 1,092 organic downloads
- ✅ **Patent-protected** — Only MCP server with patented algorithms

## 💰 Pricing

### Free Tier (No Payment Required)
- **Header:** `x-free-tier: true`
- **Tools:** `check_turboquant` (always free), limited `analyze_soil`
- **Rate Limit:** Reasonable usage for testing and evaluation
- **No API Key Needed** — Start immediately

### Credit Packs — Pay As You Go

| Pack | Price | Credits | Per-Call Rate | Best For | Buy |
|------|-------|---------|---------------|----------|-----|
| Starter | $10.00 | 1,000 | $0.01/call | Low-volume users, hobby developers | [Buy →](https://buy.stripe.com/3cIdR99oWajZdjI6EKaMU07) |
| Pro | $25.00 | 5,000 | $0.005/call | Regular users, integrations | [Buy →](https://buy.stripe.com/7sY28reJg1NtenM8MSaMU0b) |
| Enterprise | $50.00 | 25,000 | $0.002/call | High-volume users, MCP/Clawhub clients | [Buy →](https://buy.stripe.com/3cIeVd9oW1NtgvU1kqaMU09) |

### Monthly Subscriptions

| Plan | Price | Included Calls | Best For | Subscribe |
|------|-------|---------------|----------|-----------|
| Starter | $149/mo | 10,000/mo | Solo developers | [Subscribe →](https://buy.stripe.com/5kQ6oHcB88bR93s8MSaMU04) |
| Pro | $499/mo | 35,000/mo | Production apps, teams | [Subscribe →](https://buy.stripe.com/14A6oH7gO3VBcfE1kqaMU05) |
| Enterprise | $1,999/mo | 175,000+/mo | White-label, SLA, OEM | [Subscribe →](https://buy.stripe.com/eVqaEXfNkajZ6Vk0gmaMU06) |



### International Pricing

| Region | Starter | Pro | Local Payment Methods |
|--------|---------|-----|----------------------|
| **United States** | $149/mo | $499/mo | Card, Apple Pay, Google Pay, Affirm |
| **European Union** | €135/mo (VAT incl.) | €450/mo (VAT incl.) | Klarna, iDEAL, EPS, Apple/Google Pay |
| **United Kingdom** | £115/mo (VAT incl.) | £385/mo (VAT incl.) | Afterpay/Clearpay, Apple/Google Pay |
| **Australia** | AU$225/mo (GST incl.) | AU$750/mo (GST incl.) | Afterpay, Apple/Google Pay |

## 🚀 Quick Start

### Option A: Free Tier (Start Immediately)
No API key required — use `x-free-tier: true` header

**Configure Claude Desktop:**
1. Open Claude Desktop settings → Developer → MCP Servers
2. Add server:
   - URL: `https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server`
   - Headers: `x-free-tier: true`

**Configure OpenClaw:**
```yaml
mcpServers:
  leafengines:
    url: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server
    headers:
      x-free-tier: true
```

### Option B: Paid Tier (Full Access)
Get metered pricing — credit packs + monthly subscriptions

1. **Subscribe:** [Starter $149/mo →](https://buy.stripe.com/5kQ6oHcB88bR93s8MSaMU04) | [Pro $499/mo →](https://buy.stripe.com/14A6oH7gO3VBcfE1kqaMU05)
2. **Configure Claude Desktop:** Same URL, headers: `x-api-key: YOUR_PAID_API_KEY`
3. **Configure OpenClaw:**
```yaml
mcpServers:
  leafengines:
    url: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server
    headers:
      x-api-key: YOUR_PAID_API_KEY
```

## 🎯 Use Cases

### For Agronomists & Soil Scientists
- **Field analysis** — USDA data for any US county
- **Carbon credit assessment** — Proprietary compliance models
- **Partner Program:** [Sell soil reports to your clients →](https://soilcertify.com)

### For Agricultural Consultants
- **Client-ready analysis** — Soil composition, drainage, NPK recommendations
- **Sell reports to clients:** [Join Partner Program →](https://soilcertify.com) (4× markup on $25 wholesale)

### For Developers & AI Engineers
- **MCP integration** — Claude, Cursor, OpenClaw, any MCP client
- **TurboQuant** — 6x memory compression for edge/offline deployment
- **Multi-agent** — 10 tools across 4 pricing tiers

## 🔗 Related Products

- **[MCP Server](https://www.npmjs.com/package/@ancientwhispers54/leafengines-mcp-server)** — Claude Desktop, Cursor
- **[n8n Nodes](https://github.com/QWarranto/n8n-nodes-leafengines)** — n8n automation
- **[Node-RED](https://github.com/QWarranto/node-red-contrib-leafengines)** — IoT/edge
- **[QGIS Plugin](https://plugins.qgis.org/plugins/qgis_leafengines/)** — Plugin ID 4987
- **[SoilCertify](https://soilcertify.com)** — Professional soil reports, no coding required

## 📞 Support

- **API Documentation:** [app.soilsidekickpro.com/api-docs](https://app.soilsidekickpro.com/api-docs)
- **MCP Documentation:** [app.soilsidekickpro.com/mcp](https://app.soilsidekickpro.com/mcp)
- **GitHub:** [github.com/QWarranto/leafengines-claude-mcp](https://github.com/QWarranto/leafengines-claude-mcp)
- **Email:** support@soilsidekickpro.com

## 📄 License & IP

Proprietary API service. Free tier available. Patent-protected algorithms (U.S. #19/320,727, #19/544,827).

---

🌱 **LeafEngines™** | SoilSidekick Pro® | SoilCertify | SoilTech Suite, Inc.
*Space gives the picture. We give the truth.*