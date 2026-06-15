# LeafEngines ClawHub Skill — Agricultural Intelligence for OpenClaw Agents

**Patent-protected soil analysis, crop recommendations, and environmental intelligence** for OpenClaw agents. 1,092+ MCP downloads. The only skill with patented algorithms in the ClawHub ecosystem.

## ⚡ Get Started Now

**Free tier — no signup, no credit card:**
- **Test key:** `leaf-test-370df0a2e62e` (paste into config, works immediately)
- **Free header:** `x-free-tier: true` (no key needed at all)

**Ready for production?**
- [Starter — $149/mo →](https://buy.stripe.com/5kQ6oHcB88bR93s8MSaMU04)
- [Pro — $499/mo →](https://buy.stripe.com/14A6oH7gO3VBcfE1kqaMU05)

**Partner Program:** Stop building for free. Use our API to sell $100–200 soil reports to local farmers, drone pilots, and GIS communities. You buy each report for $25. [Join our Partner Program →](https://soilcertify.com)

---

## 🌾 What It Does

LeafEngines gives OpenClaw agents real-time agricultural intelligence from USDA, EPA, and NOAA data:

- **Soil Analysis** — pH, nutrients, organic matter, drainage, recommendations for any US county
- **Crop Recommendations** — Location-specific planting advice based on soil and climate
- **Environmental Impact** — Patent-pending Environmental Compatibility Score with satellite data fusion
- **Carbon Credits** — Proprietary models for compliance reporting and sustainability scoring
- **Water Quality** — EPA monitoring data and contamination risk assessment
- **TurboQuant Check** — Hardware optimization for edge/offline deployment (always free)

## 🚀 Quick Start

### Install

```bash
clawhub install leafengines
```

### Configure

```yaml
skills:
  leafengines:
    enabled: true
    config:
      api_key: leaf-test-370df0a2e62e
      base_url: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server-v2
```

**That's it.** Your OpenClaw agent now has agricultural intelligence.

## 💰 Pricing

### Free Tier — No Credit Card
- **Test key:** `leaf-test-370df0a2e62e` — works immediately
- **Free header:** `x-free-tier: true` — no key needed
- **Includes:** Basic soil analysis, county lookup, TurboQuant check
- **Try it:** [soilcertify.com →](https://soilcertify.com)

### Credit Packs — Pay As You Go

| Pack | Price | Credits | Per-Call Rate | Best For | Buy |
|------|-------|---------|---------------|----------|-----|
| Starter | $10.00 | 1,000 | $0.01/call | Low-volume users, hobby developers | [Buy →](https://buy.stripe.com/3cIdR99oWajZdjI6EKaMU07) |
| Pro | $25.00 | 5,000 | $0.005/call | Regular users, integrations | [Buy →](https://buy.stripe.com/7sY28reJg1NtenM8MSaMU0b) |
| Enterprise | $50.00 | 25,000 | $0.002/call | High-volume users, MCP/Clawhub clients | [Buy →](https://buy.stripe.com/3cIeVd9oW1NtgvU1kqaMU09) |

### Monthly Subscriptions

| Plan | Price | Included Calls | Best For | Subscribe |
|------|-------|---------------|----------|-----------|
| Starter | $149/mo | 10,000/mo | Solo developers, prototyping | [Subscribe →](https://buy.stripe.com/5kQ6oHcB88bR93s8MSaMU04) |
| Pro | $499/mo | 35,000/mo | Production apps, teams | [Subscribe →](https://buy.stripe.com/14A6oH7gO3VBcfE1kqaMU05) |
| Enterprise | $1,999/mo | 175,000+/mo | White-label, SLA, OEM | [Subscribe →](https://buy.stripe.com/eVqaEXfNkajZ6Vk0gmaMU06) |
| Enterprise Bundle | $3,499/mo | 685,000/mo | Large OEM, max volume | Contact: sales@leafengines.com |



### International Pricing

| Region | Starter | Pro | Local Payment Methods |
|--------|---------|-----|----------------------|
| **United States** | $149/mo | $499/mo | Card, Apple Pay, Google Pay, Affirm |
| **European Union** | €135/mo (VAT incl.) | €450/mo (VAT incl.) | Klarna, iDEAL, EPS, Apple/Google Pay |
| **United Kingdom** | £115/mo (VAT incl.) | £385/mo (VAT incl.) | Afterpay/Clearpay, Apple/Google Pay |
| **Australia** | AU$225/mo (GST incl.) | AU$750/mo (GST incl.) | Afterpay, Apple/Google Pay |

## 🎯 Use Cases

### For Agronomists & Soil Scientists
- **Field analysis** — USDA SSURGO data for any US county, instantly
- **Carbon credit assessment** — Proprietary models for compliance reporting
- **Environmental impact scoring** — Patent-pending satellite data fusion
- **Partner Program:** [Sell soil reports to your clients →](https://soilcertify.com)

### For Agricultural Consultants
- **Client-ready analysis** — Soil composition, drainage, NPK recommendations
- **Crop optimization** — Multi-parameter phenology for planting windows
- **Water quality assessment** — EPA data with contamination risk scores
- **Sell reports to clients:** [Join Partner Program →](https://soilcertify.com) (4× markup on $25 wholesale)

### For Developers & AI Engineers
- **OpenClaw integration** — One-command install via ClawHub
- **TurboQuant optimization** — 6x memory compression for edge/offline deployment
- **Multi-agent orchestration** — 10 tools across 4 pricing tiers
- **API access** — Direct HTTP calls to Supabase edge functions

## 🔧 Available Tools

| Tool | What It Returns | Tier |
|------|----------------|------|
| `analyze_soil` | Soil characteristics and recommendations | Free (limited) / Paid |
| `recommend_crop` | Crop suggestions based on soil analysis | Paid |
| `check_turboquant` | Hardware optimization check | Free (always) |

Full tool set (10 tools) available via MCP Server: [leafengines-mcp-server →](https://github.com/QWarranto/leafengines-claude-mcp/tree/main/leafengines-mcp-server)

## 🔗 Related Products

- **[MCP Server](https://www.npmjs.com/package/@ancientwhispers54/leafengines-mcp-server)** — Claude Desktop, Cursor integration
- **[n8n Nodes](https://github.com/QWarranto/n8n-nodes-leafengines)** — n8n business automation
- **[Node-RED Nodes](https://github.com/QWarranto/node-red-contrib-leafengines)** — IoT/edge automation
- **[QGIS Plugin](https://plugins.qgis.org/plugins/qgis_leafengines/)** — 500,000+ QGIS users (Plugin ID 4987)
- **[SoilCertify](https://soilcertify.com)** — Professional soil reports, no coding required

## 📞 Support

- **API Documentation:** [app.soilsidekickpro.com/api-docs](https://app.soilsidekickpro.com/api-docs)
- **MCP Documentation:** [app.soilsidekickpro.com/mcp](https://app.soilsidekickpro.com/mcp)
- **GitHub Issues:** [github.com/QWarranto/leafengines-claude-mcp/issues](https://github.com/QWarranto/leafengines-claude-mcp/issues)
- **Email:** support@soilsidekickpro.com
- **Partnerships:** partnerships@leafengines.com

## 📄 License & Intellectual Property

Skill code: Open source (see LICENSE). API service: Commercial with free tier. Core algorithms: Patent-protected (U.S. #19/320,727, #19/544,827).

---

🌱 **LeafEngines™** | SoilSidekick Pro® | SoilCertify | SoilTech Suite, Inc.
*Space gives the picture. We give the truth.*