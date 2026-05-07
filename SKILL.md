---
name: leafengines
version: 1.2.1
description: LeafEngines - Agricultural Intelligence with Free Tier & Founder Pricing. 1,092+ downloads. 3 tools for soil analysis, crop recommendations, and TurboQuant capabilities. Free tier available with x-free-tier header.
homepage: https://app.soilsidekickpro.com/mcp
source: https://github.com/QWarranto/leafengines-claude-mcp
metadata: {"openclaw":{"emoji":"🌱","os":["darwin","linux"],"requires":{"bins":[]},"install":[{"id":"claude-desktop","kind":"manual","steps":["1. Open Claude Desktop settings","2. Navigate to Developer → MCP Servers","3. Add new server with URL: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server","4. Add header: x-free-tier: true (FREE) OR x-api-key: YOUR_PAID_KEY (Paid)"],"label":"Configure in Claude Desktop"},{"id":"openclaw-mcp","kind":"manual","steps":["1. Choose FREE tier (x-free-tier: true) or PAID tier (get API key from Stripe checkout)","2. Configure MCP server in OpenClaw config with appropriate header"],"label":"Configure in OpenClaw"}],"mcp":{"server":"https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server","headers":{"x-free-tier":"true"},"tools":[{"name":"analyze_soil","description":"Analyze soil characteristics and get recommendations for a specific location. Requires county_fips parameter (5-digit code).","inputSchema":{"type":"object","properties":{"county_fips":{"type":"string","description":"5-digit county FIPS code (e.g., '13067' for Fulton County, GA)"},"api_key":{"type":"string","description":"Optional API key for paid features (use x-api-key header instead)"}},"required":["county_fips"]}},{"name":"recommend_crop","description":"Get crop recommendations based on soil analysis.","inputSchema":{"type":"object","properties":{"county_fips":{"type":"string","description":"5-digit county FIPS code"},"api_key":{"type":"string","description":"Optional API key for paid features"}},"required":["county_fips"]}},{"name":"check_turboquant","description":"Check if TurboQuant capabilities are available for a location (FREE). No authentication required.","inputSchema":{"type":"object","properties":{"county_fips":{"type":"string","description":"5-digit county FIPS code"}},"required":["county_fips"]}}]}}}
---

# LeafEngines MCP Server v1.2.1

**Agricultural Intelligence with Free Tier & Founder Pricing** for Claude and OpenClaw. **1,092+ downloads** since March 29.

## ⚡ Get Started Now

**Free tier — no signup, no credit card:**
- **Test key:** `leaf-test-370df0a2e62e` (works immediately)
- **Free header:** `x-free-tier: true` (no key needed)

**Ready for production? Founder pricing ends June 1, 2026:**
- [Starter — $10/mo → lifetime $49/mo lock →](https://buy.stripe.com/14A7sL30y8bR2F4fbgaMU02)
- [Pro — $49/mo → lifetime $149/mo lock →](https://buy.stripe.com/cNi3cv1WuajZcfE7IOaMU03)

**Get a professional soil report (no coding required):** [soilcertify.com →](https://soilcertify.com)

## 🌾 What It Does

**3 Agricultural Intelligence Tools:**
1. **Analyze Soil** — Soil characteristics and recommendations (requires `county_fips`)
2. **Recommend Crop** — Crop suggestions based on soil analysis
3. **Check TurboQuant** — Hardware optimization check (FREE, always, no auth)

**Why 1,092+ Developers Choose Us:**
- ✅ **Free tier available** — No API key required for testing
- ✅ **Founder pricing** — $10/mo Starter, $49/mo Pro (lifetime lock, first 100)
- ✅ **Simple integration** — 3 focused tools with clear parameters
- ✅ **Proven adoption** — 1,092 organic downloads
- ✅ **Patent-protected** — Only MCP server with patented algorithms

## 💰 Pricing

### Free Tier (No Payment Required)
- **Header:** `x-free-tier: true`
- **Tools:** `check_turboquant` (always free), limited `analyze_soil`
- **Rate Limit:** Reasonable usage for testing and evaluation
- **No API Key Needed** — Start immediately

### Pay-As-You-Go

| Tier | Price | Per-Call Rate | What You Get | Buy |
|------|-------|--------------|--------------|-----|
| Commoditized | $0.50/bundle | $0.001/call | Basic soil/weather, county lookup | [Buy →](https://buy.stripe.com/3cIdR99oWajZdjI6EKaMU07) |
| Enhanced | $1.50/bundle | $0.003/call | Environmental impact, crop suitability | [Buy →](https://buy.stripe.com/7sY28reJg1NtenM8MSaMU0b) |
| Proprietary | $5.00/bundle | $0.010/call | Planting optimization, carbon credits | [Buy →](https://buy.stripe.com/3cIeVd9oW1NtgvU1kqaMU09) |
| Exclusive | $10.00/bundle | $0.020/call | Patent-pending env compatibility scoring | [Buy →](https://buy.stripe.com/6oU4gzbx40Jp6Vk1kqaMU0a) |

### Monthly Subscriptions

| Plan | Price | Included Calls | Best For | Subscribe |
|------|-------|---------------|----------|-----------|
| **Founder Starter** | $10/mo → lifetime $49/mo | 10,000/mo | Solo developers, prototyping | [Subscribe →](https://buy.stripe.com/14A7sL30y8bR2F4fbgaMU02) |
| **Founder Pro** | $49/mo → lifetime $149/mo | 35,000/mo | Production apps, teams | [Subscribe →](https://buy.stripe.com/cNi3cv1WuajZcfE7IOaMU03) |
| Starter | $149/mo | 10,000/mo | Solo developers | [Subscribe →](https://buy.stripe.com/5kQ6oHcB88bR93s8MSaMU04) |
| Pro | $499/mo | 35,000/mo | Production apps, teams | [Subscribe →](https://buy.stripe.com/14A6oH7gO3VBcfE1kqaMU05) |
| Enterprise | $1,999/mo | 175,000+/mo | White-label, SLA, OEM | [Subscribe →](https://buy.stripe.com/eVqaEXfNkajZ6Vk0gmaMU06) |

> ⏰ **Founder pricing expires June 1, 2026.** First 100 customers lock lifetime rates.

### International Pricing

| Region | Starter | Pro | Local Payment Methods |
|--------|---------|-----|----------------------|
| **United States** | $49/mo | $149/mo | Card, Apple Pay, Google Pay, Affirm |
| **European Union** | €45/mo (VAT incl.) | €135/mo (VAT incl.) | Klarna, iDEAL, EPS, Apple/Google Pay |
| **United Kingdom** | £38/mo (VAT incl.) | £115/mo (VAT incl.) | Afterpay/Clearpay, Apple/Google Pay |
| **Australia** | AU$75/mo (GST incl.) | AU$225/mo (GST incl.) | Afterpay, Apple/Google Pay |

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
Get Founder pricing — first 100 customers get lifetime lock

1. **Subscribe:** [Starter $10/mo →](https://buy.stripe.com/14A7sL30y8bR2F4fbgaMU02) | [Pro $49/mo →](https://buy.stripe.com/cNi3cv1WuajZcfE7IOaMU03)
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
- **Get professional reports without coding:** [soilcertify.com →](https://soilcertify.com)

### For Agricultural Consultants
- **Client-ready analysis** — Soil composition, drainage, NPK recommendations
- **Sell reports to clients:** [soilcertify.com →](https://soilcertify.com) (172%+ profit margin at $29/mo)

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
