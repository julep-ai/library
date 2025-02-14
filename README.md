<div align="center" id="top">
<img src="https://socialify.git.ci/julep-ai/julep/image?description=1&descriptionEditable=Serverless%20AI%20Workflows%20for%20Data%20%26%20ML%20Teams&font=Source%20Code%20Pro&logo=https%3A%2F%2Fraw.githubusercontent.com%2Fjulep-ai%2Fjulep%2Fdev%2F.github%2Fjulep-logo.svg&owner=1&forks=1&pattern=Solid&stargazers=1&theme=Auto" alt="julep" />

<br>
  <p>
    <a href="https://dashboard.julep.ai">
      <img src="https://img.shields.io/badge/Get_API_Key-FF5733?style=logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAxTDMgNXYxNGw5IDQgOS00VjVsLTktNHptMCAyLjh2MTYuNEw1IDE2LjJWNi44bDctMy4yem0yIDguMmwtMi0yLTIgMiAyIDIgMi0yeiIvPjwvc3ZnPg==" alt="Get API Key" height="28">
    </a>
    <span>&nbsp;</span>
    <a href="https://docs.julep.ai">
      <img src="https://img.shields.io/badge/Documentation-4B32C3?style=logo=gitbook&logoColor=white" alt="Documentation" height="28">
    </a>
  </p>
  <p>
   <a href="https://www.npmjs.com/package/@julep/sdk"><img src="https://img.shields.io/npm/v/%40julep%2Fsdk?style=social&amp;logo=npm&amp;link=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2F%40julep%2Fsdk" alt="NPM Version" height="28"></a>
    <span>&nbsp;</span>
    <a href="https://pypi.org/project/julep"><img src="https://img.shields.io/pypi/v/julep?style=social&amp;logo=python&amp;label=PyPI&amp;link=https%3A%2F%2Fpypi.org%2Fproject%2Fjulep" alt="PyPI - Version" height="28"></a>
    <span>&nbsp;</span>
    <a href="https://hub.docker.com/u/julepai"><img src="https://img.shields.io/docker/v/julepai/agents-api?sort=semver&amp;style=social&amp;logo=docker&amp;link=https%3A%2F%2Fhub.docker.com%2Fu%2Fjulepai" alt="Docker Image Version" height="28"></a>
    <span>&nbsp;</span>
    <a href="https://choosealicense.com/licenses/apache/"><img src="https://img.shields.io/github/license/julep-ai/julep" alt="GitHub License" height="28"></a>
  </p>
  
  <h3>
    <a href="https://discord.com/invite/JTSBGRZrzj" rel="dofollow">Discord</a>
    ·
    <a href="https://x.com/julep_ai" rel="dofollow">𝕏</a>
    ·
    <a href="https://www.linkedin.com/company/julep-ai" rel="dofollow">LinkedIn</a>
  </h3>
</div>

<div align="center">
  <h3><i>Serverless AI Workflows for Data & ML Teams</i></h3>
</div>


---

Welcome to the **Julep AI Workflow Library**! This repository houses production-ready workflows that showcase the power and flexibility of Julep's AI automation capabilities. Whether you're building chatbots, automation tools, or complex AI systems, you'll find examples and templates to accelerate your development.

## 🚀 Quick Start

There are three ways to use the workflows:

1. **Julep CLI**: This is useful if you want to use the workflows in your own projects. To learn more about the Julep CLI, please refer to the [Julep CLI Documentation](https://docs.julep.ai/docs/julepcli/introduction).
   
2. **Julep SDK**: This is useful if you want to use the workflows in the Julep platform. To learn more about the Julep SDK, please refer to the [Julep Quickstart Documentation](https://docs.julep.ai/docs/introduction/julep).
   
3. **Julep Dashboard**: This is useful if you want to use the workflows in the Julep platform. To learn more about the Julep Dashboard, please refer to the [Julep Dashboard Documentation](https://dashboard.julep.ai/).

---

## 🛠️ Workflow Directory Structure

Each workflow follows a standardized structure:

```plaintext
workflow-name/
├── README.md         # Documentation and usage instructions
├── julep.yaml        # Workflow configuration and entrypoint
└── src/              # Source directory
    ├── agents/       # Agent definitions
    │   └── agent.yaml
    └── tasks/        # Task definitions
        └── task.yaml
    └── tools/        # Tools definitions
        └── tool.yaml
```
---

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

---

## 🤝 Contributing

We love contributions! Here's how you can help:

1. Fork the repository
2. Create a new workflow directory
3. Add required files (README.md, julep.yaml, src/agents/agent.yaml, src/tasks/task.yaml, src/tools/tool.yaml)
4. Submit a pull request with your changes for review

See our [Contributing Guidelines](CONTRIBUTING.md) for more details.

Your contributions, big or small, are valuable to us. Let's build something amazing together! 🚀

<h4>Our Amazing Contributors:</h4>

<a href="https://github.com/julep-ai/library/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=julep-ai/library" />
</a>

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <sub>Built with ❤️ by the Julep AI team</sub>
</div>
