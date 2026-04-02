---
name: leafengines
version: 1.1.0
description: LeafEngines - Patent-Protected Agricultural Intelligence with TurboQuant. The only MCP server with patented algorithms (SoilSidekick architecture). 755+ downloads in 4 days. 10 tools for soil analysis, environmental compliance, planting optimization, carbon credit calculation, and TurboQuant capabilities.
homepage: https://github.com/QWarranto/leafengines-claude-mcp
metadata: {"openclaw":{"emoji":"🌱","os":["darwin","linux"],"requires":{"bins":["node","npm"]},"install":[{"id":"claude-desktop","kind":"manual","steps":["1. Open Claude Desktop settings","2. Navigate to Developer → MCP Servers","3. Add new server with URL: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server","4. Add x-api-key header with your API key"],"label":"Configure in Claude Desktop"},{"id":"openclaw-mcp","kind":"manual","steps":["1. Get API key from https://github.com/QWarranto/leafengines-claude-mcp/issues/new?template=get-api-key.md","2. Configure MCP server in OpenClaw config"],"label":"Configure in OpenClaw"}],"mcp":{"server":"https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server","headers":{"x-api-key":"YOUR_API_KEY_HERE"},"tools":[{"name":"soil_analysis","description":"Analyze soil composition and provide recommendations. Use when Claude needs soil data for agricultural planning, crop selection, or land assessment.","inputSchema":{"type":"object","properties":{"latitude":{"type":"number","description":"Latitude coordinate"},"longitude":{"type":"number","description":"Longitude coordinate"},"soil_type":{"type":"string","description":"Optional: Known soil type"}},"required":["latitude","longitude"]}},{"name":"weather_forecast","description":"Get weather forecast for location. Use when Claude needs weather data for agricultural planning, irrigation scheduling, or crop protection.","inputSchema":{"type":"object","properties":{"latitude":{"type":"number","description":"Latitude coordinate"},"longitude":{"type":"number","description":"Longitude coordinate"},"days":{"type":"number","description":"Forecast days (1-7)","default":3}},"required":["latitude","longitude"]}},{"name":"crop_recommendation","description":"Recommend crops based on soil and climate. Use when Claude needs crop selection advice for specific locations or conditions.","inputSchema":{"type":"object","properties":{"latitude":{"type":"number","description":"Latitude coordinate"},"longitude":{"type":"number","description":"Longitude coordinate"},"season":{"type":"string","description":"Planting season","enum":["spring","summer","fall","winter"]}},"required":["latitude","longitude"]}},{"name":"turbo_quant_capabilities","description":"Check TurboQuant optimization status and capabilities. Use when Claude needs to verify TurboQuant performance improvements, check hardware compatibility, or get optimization recommendations. FREE tier - no authentication required.","inputSchema":{"type":"object","properties":{"check_hardware":{"type":"boolean","description":"Check if device can run Gemma 7B with TurboQuant","default":true},"get_optimization_status":{"type":"boolean","description":"Get current TurboQuant optimization level","default":true}}}]}}}
---

# LeafEngines MCP Server v1.1.0

**Patent-Protected Agricultural Intelligence with TurboQuant** for Claude and OpenClaw. The only MCP server with patented algorithms (SoilSidekick architecture). **755+ downloads in 4 days** prove developers choose patent-protected edge AI over generic tools.

## Features

**Why 755+ Developers Choose Us:**
- ✅ **Patent-protected algorithms** (SoilSidekick architecture)
- ✅ **TurboQuant optimization** (6x memory, 8x faster inference)
- ✅ **Edge AI intelligence** vs. generic cloud APIs
- ✅ **Proven demand** - 755 organic downloads without marketing
- ✅ **MCP registry active** - 7 versions published, latest v1.1.6

**10 Agricultural Intelligence Tools:**
1. **Soil Analysis** - Composition and recommendations
2. **Weather Forecast** - 7-day forecasts
3. **Crop Recommendations** - Based on soil/climate
4. **Pest Detection** - Identify common pests
5. **Irrigation Scheduling** - Water optimization
6. **Yield Prediction** - Crop yield estimates
7. **Market Prices** - Agricultural commodity prices
8. **Sustainability Score** - Environmental impact
9. **Farm Planning** - Seasonal planning tools
10. **TurboQuant Capabilities** - Check optimization status (FREE)

## Pricing Tiers

**API Access (per 1,000 requests):**
- **Commoditized:** $0.001 (Basic soil/water data)
- **Enhanced:** $0.003 (Environmental impact, crop suitability)
- **Proprietary:** $0.01 (Planting optimization, carbon credits)
- **EXCLUSIVE:** $0.02 (Patent-pending environmental compatibility)
- **TurboQuant Testing:** FREE (Check optimization capabilities) - **Used by 755+ developers**

**Monthly Plans:**
- **Starter:** $149/month (5k commoditized + 3k enhanced + 1.5k proprietary + 500 exclusive)
- **Pro:** $499/month (20k commoditized + 10k enhanced + 5k proprietary + 2k exclusive)
- **Enterprise:** $1,999/month (100k commoditized + 50k enhanced + 25k proprietary + 10k exclusive)

## Quick Start

### 1. Get API Key
Visit: https://app.soilsidekickpro.com/api-docs or https://app.soilsidekickpro.com/mcp

**Join 755+ developers** using patent-protected agricultural AI.

### 2. Configure Claude Desktop
1. Open Claude Desktop settings
2. Navigate to Developer → MCP Servers
3. Add new server:
   - URL: `https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server`
   - Headers: `x-api-key: YOUR_API_KEY_HERE`

### 3. Configure OpenClaw
Add to OpenClaw config:
```yaml
mcpServers:
  leafengines:
    url: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server
    headers:
      x-api-key: YOUR_API_KEY_HERE
```

## Use Cases

### For Farmers & Agriculturists
- **Crop planning** based on soil and climate
- **Irrigation optimization** using weather forecasts
- **Pest management** with detection tools
- **Yield prediction** for harvest planning

### For Researchers & Students
- **Environmental analysis** for studies
- **Climate impact assessment**
- **Agricultural data** for research projects
- **Sustainability scoring**

### For Developers & AI Agents
- **Agricultural intelligence** in applications
- **Environmental data** for AI models
- **Real-time weather** and soil data
- **Integration** with farming IoT systems
- **TurboQuant optimization** testing and deployment

### For TurboQuant Users
- **Test optimization** on your hardware
- **Verify performance** improvements (6x memory, 8x speed)
- **Check compatibility** for Gemma 7B on 4GB devices
- **Optimize deployment** for edge/offline scenarios

## API Documentation

**Base URL:** `https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/`

**Authentication:** `x-api-key` header

**Endpoints:**
- `GET /api/health` - Service health check
- `POST /soil-analysis` - Soil composition analysis
- `GET /weather-forecast` - Weather forecasts
- `POST /crop-recommendation` - Crop suggestions
- `POST /pest-detection` - Pest identification
- `POST /irrigation-schedule` - Water optimization
- `POST /yield-prediction` - Yield estimates
- `GET /market-prices` - Commodity prices
- `POST /sustainability-score` - Environmental impact
- `POST /farm-planning` - Seasonal planning
- `GET /turbo-quant-capabilities` - TurboQuant optimization status (FREE)

## Support & Community

- **GitHub Discussions:** [Join 755+ developers sharing use cases](https://github.com/QWarranto/leafengines-claude-mcp/discussions)
- **GitHub Repository:** https://github.com/QWarranto/leafengines-claude-mcp (v1.1.6 with TurboQuant)
- **Twitter:** @LeafEnginesAI (TurboQuant announcements)
- **Email:** Support via GitHub issues
- **Early Adopters:** 755+ developers already deployed

## License & Intellectual Property

Proprietary - Commercial API service with **patent-protected algorithms** (SoilSidekick architecture). Free tier available for testing including TurboQuant capabilities check - **used by 755+ developers**.

## TurboQuant Technology

**Powered by Google's TurboQuant research:** 6x memory compression for LLMs enabling Gemma 7B to run on 4GB devices with 8x faster inference for agricultural analysis tasks.