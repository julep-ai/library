<div align="center" id="top">
 <img src="https://socialify.git.ci/julep-ai/julep/image?description=1&descriptionEditable=Rapidly%20build%20AI%20workflows%20and%20agents&font=Source%20Code%20Pro&logo=https%3A%2F%2Fraw.githubusercontent.com%2Fjulep-ai%2Fjulep%2Fdev%2F.github%2Fjulep-logo.svg&owner=1&forks=1&pattern=Solid&stargazers=1&theme=Auto" alt="julep" width="640" height="320" />
</div>

<p align="center">
  <br />
  <a href="https://docs.julep.ai" rel="dofollow">Explore Docs (wip)</a>
  ·
  <a href="https://discord.com/invite/JTSBGRZrzj" rel="dofollow">Discord</a>
  ·
  <a href="https://x.com/julep_ai" rel="dofollow">𝕏</a>
  ·
  <a href="https://www.linkedin.com/company/julep-ai" rel="dofollow">LinkedIn</a>
</p>

<p align="center">
    <a href="https://www.npmjs.com/package/@julep/sdk"><img src="https://img.shields.io/npm/v/%40julep%2Fsdk?style=social&amp;logo=npm&amp;link=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2F%40julep%2Fsdk" alt="NPM Version"></a>
    <span>&nbsp;</span>
    <a href="https://pypi.org/project/julep"><img src="https://img.shields.io/pypi/v/julep?style=social&amp;logo=python&amp;label=PyPI&amp;link=https%3A%2F%2Fpypi.org%2Fproject%2Fjulep" alt="PyPI - Version"></a>
    <span>&nbsp;</span>
    <a href="https://hub.docker.com/u/julepai"><img src="https://img.shields.io/docker/v/julepai/agents-api?sort=semver&amp;style=social&amp;logo=docker&amp;link=https%3A%2F%2Fhub.docker.com%2Fu%2Fjulepai" alt="Docker Image Version"></a>
    <span>&nbsp;</span>
    <a href="https://choosealicense.com/licenses/apache/"><img src="https://img.shields.io/github/license/julep-ai/julep" alt="GitHub License"></a>
</p>

</div>

# Julep AI - Workflow Library

Welcome to the **Julep AI Workflow Library**! This repository houses production-ready workflows that showcase the power and flexibility of Julep's AI automation capabilities. Whether you're building chatbots, automation tools, or complex AI systems, you'll find examples and templates to accelerate your development.

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/julep-ai/julep.git

# Navigate to the workflow library
cd julep/library

# Choose a workflow and follow its README
cd workflow-name
```

## 📚 Workflow Categories

### 🤖 AI & Chat

- **[Smart Researcher With WebSearch](./online-researcher)** - AI-powered research assistant
- **[Personalized Research Assistant](./personalized-research-assistant)** - Personalized research paper recommendation assistant based on user persona and research interests
- **[Trip Planner](./trip-planner)** - Travel planning with weather and tourist information

### 🔧 Automation & Integration

- **[Website Crawler Spider](./website-crawler-spider)** - Automated web content extraction
- **[External Tools and APIs Integration](./integrating-external-tools-and-apis)** - Third-party service integration
- **[Browser Use](./browser-use)** - Headless browser automation and web interactions
- **[Video Processing](./video-processing-natural-lang)** - Video processing with input taken in the form of natural language

### 🎯 Content & Marketing

- **[Trending Reels Hook Generator](./trending-reels-hook-generator)** - Viral content creation
- **[Sarcastic Headline Generator](./sarcastic-headline-generator)** - Engaging headline creation
- **[Profiling and Recommending](./profiling-recommending)** - Profiling and recommending workflow

### 🧩 Miscellaneous

- **[Hello World](./hello-world)** - Basic workflow demonstration
- **[Multi-Step Task](./multi-step-task)** - Multi-step task creation for research and summarization
- **[Email Assistant](./email-assistant)** - Email management for questions and inquiries asked by users in the Devfest event
- **[Analyst](./analyst)** - Data analysis and insights generation

## 🛠️ Workflow Directory Structure

Each workflow follows a standardized structure:

```plaintext
workflow-name/
├── README.md           # Documentation and usage instructions
├── julep.yaml         # Workflow configuration and entrypoint
└── src/              # Source directory
    ├── agents/       # Agent definitions
    │   └── agent.yaml
    └── tasks/        # Task definitions
        └── task.yaml
    └── tools/        # Tools definitions
        └── tool.yaml
```

## 🤝 Contributing

We love contributions! Here's how you can help:

1. Fork the repository
2. Create a new workflow directory
3. Add required files (README.md, julep.toml, workflow definition)
4. Submit a pull request

See our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## 📖 Documentation

- [Julep Documentation](https://docs.julep.ai)
- [API Reference](https://github.com/julep-ai/julep)

## 🤝 Support & Community

- [Discord Community](https://discord.com/invite/JTSBGRZrzj)
- [GitHub Issues](https://github.com/julep-ai/julep/issues)
- Email: [hey@julep.ai](mailto:hey@julep.ai)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <sub>Built with ❤️ by the Julep AI team</sub>
</div>
