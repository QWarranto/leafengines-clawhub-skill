# Contributing to LeafEngines ClawHub Skill

Thank you for your interest in contributing to the LeafEngines ClawHub Skill! This document provides guidelines for contributing to this OpenClaw skill.

## 🌱 Project Overview

This skill enables OpenClaw agents to access LeafEngines' agricultural intelligence platform. It's a **thin integration layer** that:
- Provides OpenClaw skill definitions
- Handles authentication and API communication
- Maps LeafEngines API endpoints to OpenClaw tools
- Contains **NO proprietary algorithms or IP**

## 🚀 Getting Started

### Prerequisites
- OpenClaw installation
- Basic understanding of OpenClaw skills
- Git and GitHub account

### Development Setup
```bash
# Clone the repository
git clone https://github.com/QWarranto/leafengines-claude-mcp.git
cd leafengines-claude-mcp/leafengines-clawhub-skill

# The skill is ready to use
```

## 📝 Contribution Guidelines

### 1. Code Style
- Follow existing skill patterns in `SKILL.md`
- Use YAML for configuration files
- Include clear descriptions for all tools
- Test with OpenClaw before submitting

### 2. Skill Structure
- **SKILL.md:** Main skill definition (OpenClaw format)
- **README.md:** User documentation
- **references/:** Reference materials
- **scripts/:** Helper scripts (if any)

### 3. Pull Request Process
1. **Fork the repository**
2. **Create a feature branch:** `git checkout -b feature/amazing-feature`
3. **Commit your changes:** `git commit -m 'Add some amazing feature'`
4. **Push to the branch:** `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### 4. What to Contribute
- **Bug fixes:** Report and fix issues
- **Documentation:** Improve README, comments, or guides
- **Tool enhancements:** Add new tool definitions
- **Configuration improvements:** Better OpenClaw integration
- **Examples:** More usage examples

### 5. What NOT to Contribute
- **Proprietary algorithms:** Keep all intelligence in the backend API
- **Hardcoded API keys:** Use environment variables or configuration
- **IP-sensitive code:** This is an integration layer only
- **Business logic:** All intelligence remains in LeafEngines API

## 🐛 Reporting Issues

### Bug Reports
When reporting bugs, please include:
1. **Environment:** OpenClaw version, OS, skill version
2. **Steps to reproduce:** Clear, step-by-step instructions
3. **Expected behavior:** What you expected to happen
4. **Actual behavior:** What actually happened
5. **Logs:** Any error messages or console output

### Feature Requests
For feature requests:
1. **Use case:** Describe the problem you're trying to solve
2. **Proposed solution:** How you think it should work
3. **Alternatives considered:** Other approaches you've considered

## 🔧 Development Workflow

### Testing
```bash
# Test with OpenClaw
# 1. Copy skill to OpenClaw skills directory
# 2. Restart OpenClaw
# 3. Verify skill loads correctly
# 4. Test tool execution
```

### Documentation
- Update `README.md` for user-facing changes
- Update `SKILL.md` for OpenClaw skill changes
- Add examples in appropriate sections

## 📄 License

By contributing, you agree that your contributions will be licensed under the same license as the project. See the main repository for license details.

## 🤝 Code of Conduct

### Be Respectful
- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Gracefully accept constructive criticism
- Focus on what is best for the community

### No Harassment
Harassment of any kind will not be tolerated, including:
- Offensive comments related to gender, gender identity, sexual orientation, disability, physical appearance, race, religion
- Sexual images in public spaces
- Deliberate intimidation, stalking, or following
- Harassing photography or recording
- Sustained disruption of discussions
- Inappropriate physical contact
- Unwelcome sexual attention

## 🔗 Resources

- **GitHub Repository:** [https://github.com/QWarranto/leafengines-claude-mcp](https://github.com/QWarranto/leafengines-claude-mcp)
- **LeafEngines API:** [https://app.soilsidekickpro.com/api-docs](https://app.soilsidekickpro.com/api-docs)
- **OpenClaw Documentation:** [https://docs.openclaw.ai](https://docs.openclaw.ai)
- **ClawHub:** [https://clawhub.ai](https://clawhub.ai)

## 📞 Getting Help

- **GitHub Issues:** For bug reports and feature requests
- **Pull Requests:** For code contributions
- **OpenClaw Community:** Discord or community forums

---

Thank you for contributing to agricultural AI accessibility in OpenClaw! 🌱