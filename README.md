# LeafEngines ClawHub Skill

🌱 **Patent-Protected Agricultural Intelligence for OpenClaw Agents** - The only MCP server with patented algorithms. 755+ developers agree.

## Overview

This ClawHub skill enables OpenClaw agents to access LeafEngines' **patent-protected agricultural intelligence platform** (SoilSidekick architecture), providing tools for soil analysis, weather forecasting, crop recommendations, and environmental impact assessment. 

**Why 755 developers chose us in 4 days:**
- ✅ **Patent-protected algorithms** (not just another API wrapper)
- ✅ **TurboQuant technology** for 6x memory reduction
- ✅ **Edge AI intelligence** vs. generic cloud APIs
- ✅ **Proven demand** - 755 organic downloads without marketing

## Features

### 🚀 **TurboQuant Performance**
- **6x memory reduction** with Google TurboQuant optimization
- **8x faster inference** for agricultural analysis
- **Gemma 7B on 4GB devices** (previously required 8GB+)
- **Cloud-equivalent performance** on edge devices

### 🌾 **Agricultural Intelligence Tools**
1. **Soil Analysis** - Composition and recommendations
2. **Weather Forecast** - 7-day agricultural weather data
3. **Crop Recommendations** - Based on soil and climate conditions
4. **Environmental Impact** - Sustainability and carbon footprint analysis
5. **TurboQuant Capabilities** - FREE hardware optimization check

### 💰 **Pricing Tiers**
- **FREE Tier:** `turbo_quant_capabilities` tool (no API key required) - **Used by 755+ developers**
- **Paid Tiers:** From $0.001/call for patent-protected soil analysis, weather forecasts, etc.
- **Monthly Plans:** Save 30-70% with Starter ($149), Pro ($499), or Enterprise ($1,999) plans

## Installation

### For OpenClaw Users
```bash
# Install via ClawHub - Join 755+ developers using patent-protected agricultural AI
clawhub install leafengines

# Or manually add to skills directory
```

### For Developers
```bash
# Clone the repository
git clone https://github.com/QWarranto/leafengines-claude-mcp.git
cd leafengines-claude-mcp/leafengines-clawhub-skill

# The skill is ready to use with OpenClaw
```

## Configuration

### 1. Get API Key
Visit: [https://app.soilsidekickpro.com/api-docs](https://app.soilsidekickpro.com/api-docs) or [https://app.soilsidekickpro.com/mcp](https://app.soilsidekickpro.com/mcp)

### 2. Configure OpenClaw
Add to your OpenClaw configuration:

```yaml
skills:
  leafengines:
    enabled: true
    config:
      api_key: YOUR_API_KEY_HERE
      base_url: https://wzgnxkoeqzvueypwzvyn.supabase.co/functions/v1/mcp-server-v2
```

### 3. Environment Variables
```bash
export LEAFENGINES_API_KEY="your_api_key_here"
```

## Usage Examples

### Soil Analysis
```yaml
# Agent request pattern
- tool: leafengines_soil_analysis
  params:
    latitude: 33.7490
    longitude: -84.3880
    soil_type: "loam"
```

### Weather Forecast
```yaml
- tool: leafengines_weather_forecast
  params:
    latitude: 33.7490
    longitude: -84.3880
    days: 3
```

### Crop Recommendation
```yaml
- tool: leafengines_crop_recommendation
  params:
    latitude: 33.7490
    longitude: -84.3880
    season: "spring"
```

### FREE TurboQuant Check
```yaml
- tool: leafengines_turbo_quant_capabilities
  params:
    check_hardware: true
    get_optimization_status: true
```

## Use Cases

### For Agricultural Agents
- **Farm planning** and crop selection
- **Weather-based** irrigation scheduling
- **Soil health** monitoring and recommendations
- **Environmental compliance** and sustainability reporting

### For Research Agents
- **Agricultural data** analysis and research
- **Climate impact** studies
- **Crop yield** prediction models
- **Environmental policy** analysis

### For Development Agents
- **API integration** testing
- **Performance benchmarking** with TurboQuant
- **Agricultural application** development
- **IoT system** integration

## API Integration

### MCP Server (Model Context Protocol)
LeafEngines is also available as an MCP server for Claude Desktop and other MCP-compatible clients:

```bash
# Install MCP server globally
npm install -g @ancientwhispers54/leafengines-mcp-server

# Run the server
leafengines-mcp-server
```

### MCP Registry Listing
- **Name:** `io.github.QWarranto/leafengines`
- **Version:** 1.1.6 (latest), 7 versions published
- **Registry:** [https://registry.modelcontextprotocol.io](https://registry.modelcontextprotocol.io)
- **Status:** ✅ **Active** with 755+ downloads in first 4 days

## Support & Resources

### Documentation
- **API Documentation:** [https://app.soilsidekickpro.com/api-docs](https://app.soilsidekickpro.com/api-docs)
- **MCP Documentation:** [https://app.soilsidekickpro.com/mcp](https://app.soilsidekickpro.com/mcp)
- **MCP Server:** [https://www.npmjs.com/package/@ancientwhispers54/leafengines-mcp-server](https://www.npmjs.com/package/@ancientwhispers54/leafengines-mcp-server)
- **GitHub Repository:** [https://github.com/QWarranto/leafengines-claude-mcp](https://github.com/QWarranto/leafengines-claude-mcp)

### Community
- **GitHub Discussions:** [Join 755+ developers sharing use cases](https://github.com/QWarranto/leafengines-claude-mcp/discussions)
- **GitHub Issues:** Bug reports and feature requests
- **Twitter:** @LeafEnginesAI for updates
- **Early Adopters:** 755+ developers already deployed

### Getting Help
1. Check the [API documentation](https://app.soilsidekickpro.com/api-docs) or [MCP documentation](https://app.soilsidekickpro.com/mcp)
2. Open a [GitHub issue](https://github.com/QWarranto/leafengines-claude-mcp/issues)
3. Test with the FREE `turbo_quant_capabilities` tool first

## License & Intellectual Property

This skill integrates with the LeafEngines API service. The skill code is open source, while the API service has commercial terms and **patent-protected algorithms**.

- **Skill Code:** Open source (see LICENSE file)
- **API Service:** Commercial with FREE tier available
- **Core Algorithms:** **Patent-protected** (SoilSidekick architecture)
- **TurboQuant Technology:** Based on Google research (6x memory compression)
- **Market Validation:** 755+ downloads in first 4 days

## Changelog

### v1.1.0 (Current)
- Initial ClawHub skill release
- Integration with LeafEngines MCP server v1.1.6
- **Patent-protected agricultural AI algorithms**
- TurboQuant performance optimization
- 5 agricultural intelligence tools
- FREE tier with `turbo_quant_capabilities`
- **755+ downloads in first 4 days**

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Related Projects

- **LeafEngines MCP Server:** [npm package](https://www.npmjs.com/package/@ancientwhispers54/leafengines-mcp-server)
- **LeafEngines Claude Integration:** [GitHub](https://github.com/QWarranto/leafengines-claude-mcp)
- **SoilSidekick Pro:** [Web Application](https://app.soilsidekickpro.com)
- **MCP Documentation:** [https://app.soilsidekickpro.com/mcp](https://app.soilsidekickpro.com/mcp)

---

🌱 **Happy farming with AI!** Powered by TurboQuant technology.