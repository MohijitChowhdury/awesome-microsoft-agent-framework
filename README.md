# 🤖 Awesome Microsoft Agent Framework [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

This repository contains a curated [Awesome List](https://github.com/sindresorhus/awesome) and general information on Microsoft Agent Framework for building AI agents and multi-agent workflows.

Microsoft Agent Framework is an open-source development kit for building AI agents and multi-agent workflows for .NET and Python. It brings together and extends ideas from Semantic Kernel and AutoGen projects, combining their strengths while adding new capabilities. Built by the same teams, it is the unified foundation for building AI agents going forward.

## Content

- [ℹ️ General Information on Microsoft Agent Framework](#ℹ%EF%B8%8F-general-information-on-microsoft-agent-framework)
- [🚀 Getting Started](#-getting-started)
- [📚 Official Documentation](#-official-documentation)
- [🎥 Video Resources](#-video-resources)
- [📖 Blog Posts & Articles](#-blog-posts--articles)
- [🔧 Development Resources](#-development-resources)
- [🏢 Enterprise & Production](#-enterprise--production)
- [🧪 Examples & Samples](#-examples--samples)
- [🛠️ Tools & Frameworks](#-tools--frameworks)
- [📊 Monitoring & Observability](#-monitoring--observability)
- [🔗 Related Technologies](#-related-technologies)

## ℹ️ General Information on Microsoft Agent Framework

Microsoft Agent Framework is a comprehensive set of .NET and Python libraries that reduces the complexity of agent development. Whether you're building a simple chatbot or orchestrating multiple AI agents in complex workflows, Microsoft Agent Framework provides the tools you need to:

- **Build agents** with minimal boilerplate code
- **Orchestrate multi-agent workflows** with ease
- **Host and deploy agents** using familiar .NET and Python patterns
- **Monitor and observe** agent behavior in production

**Key Features:**

1. **Multi-language Support:** Full framework support for both Python and C#/.NET implementations with consistent APIs
2. **Graph-based Workflows:** Connect agents and deterministic functions using data flows with streaming, checkpointing, human-in-the-loop, and time-travel capabilities
3. **Enterprise Ready:** Built-in observability, approvals, security, and long-running durability
4. **Open Standards:** MCP, A2A, and OpenAPI ensure agents are portable and vendor-neutral
5. **Extensible Design:** Modular by design, with connectors, pluggable memory, and declarative agent definitions

**Built on Proven Foundations:**

Microsoft Agent Framework leverages established technologies:
- **Semantic Kernel** – Provides robust orchestration
- **AutoGen** – Enables advanced multi-agent collaboration and cutting-edge research-driven techniques
- **Microsoft.Extensions.AI** – Delivers standardized AI building blocks for .NET

## 🚀 Getting Started

### Installation

**Python:**
```bash
pip install agent-framework --pre
```

**C#/.NET:**
```bash
dotnet add package Microsoft.Agents.AI
```

### Quick Start Resources

- [Microsoft Agent Framework GitHub Repository](https://github.com/microsoft/agent-framework) - Official source code and examples
- [Quick Start Guide](https://learn.microsoft.com/en-us/agent-framework/tutorials/quick-start) - Get started with a simple agent
- [Hello World Agents Sample](https://aka.ms/dotnet/agent-framework/helloworld) - Try it out in GitHub Codespaces

## 📚 Official Documentation

- [Official Documentation Hub](https://learn.microsoft.com/en-us/agent-framework/) - Complete documentation portal
- [Microsoft Agent Framework Overview](https://aka.ms/AgentFramework/docs) - High-level overview and concepts
- [Tutorials](https://learn.microsoft.com/agent-framework/tutorials/overview) - Step-by-step tutorials
- [User Guide](https://learn.microsoft.com/en-us/agent-framework/user-guide/overview) - In-depth user guide for building agents and workflows
- [Migration from Semantic Kernel](https://learn.microsoft.com/en-us/agent-framework/migration-guide/from-semantic-kernel) - Guide to migrate from Semantic Kernel
- [Migration from AutoGen](https://learn.microsoft.com/en-us/agent-framework/migration-guide/from-autogen) - Guide to migrate from AutoGen

## 🎥 Video Resources

- [Microsoft Agent Framework Introduction (30 min)](https://aka.ms/AgentFramework/OpenAtMicrosoft) - Full framework introduction
- [AI Show Episodes](https://aka.ms/AgentFramework/AIShow) - Microsoft AI Show coverage
- [DevUI in Action (1 min)](https://www.youtube.com/watch?v=mOAaGY4WPvc) - Interactive developer UI demo

## 📖 Blog Posts & Articles

### Official Microsoft Blogs

- [Introducing Microsoft Agent Framework](https://azure.microsoft.com/en-us/blog/introducing-microsoft-agent-framework/) - Azure AI + machine learning Blog
- [Introducing Microsoft Agent Framework: The Open-Source Engine for Agentic AI Apps](https://devblogs.microsoft.com/foundry/introducing-microsoft-agent-framework-the-open-source-engine-for-agentic-ai-apps/) - Azure AI Foundry Blog
- [Introducing Microsoft Agent Framework (Preview): Making AI Agents Simple for Every Developer](https://devblogs.microsoft.com/dotnet/introducing-microsoft-agent-framework-preview/) - .NET Blog announcement


### Key Concepts

- **Agents and Workflows:** Understanding the two core building blocks
- **Multi-Agent Orchestration:** Sequential, concurrent, handoff, and group chat patterns
- **Tool Integration:** Connecting agents to external APIs and services
- **Enterprise Deployment:** Production-ready hosting and monitoring

## 🔧 Development Resources

### Core Components

- **AI Agents:** Individual agents that use LLMs to process inputs, call tools, and generate responses
- **Workflows:** Graph-based workflows that connect multiple agents and functions
- **Tools:** Integration with external APIs, MCP servers, and custom functions
- **Middleware:** Flexible system for request/response processing and custom pipelines
- **Memory & Context:** Thread-based state management and context providers

### Supported Providers

- **Azure OpenAI**
- **OpenAI**
- **GitHub Models**
- **Azure AI Foundry**
- **Ollama**
- **Many others through Microsoft.Extensions.AI**

### Articles & Tutorials

- [Agent Framework Demos Day 1: Intercepting Function Calls](https://www.linkedin.com/pulse/agent-framework-demos-day-1-intercepting-function-calls-dibia-phd-sbuqc) - Practical guide to intercepting and handling function calls in Microsoft Agent Framework

## 🏢 Enterprise & Production

### Production Features

- **Observability:** Built-in OpenTelemetry integration for distributed tracing and monitoring
- **Security & Compliance:** Azure AI Content Safety integration, Entra ID authentication
- **Long-running Durability:** Agent threads and workflows can pause, resume, and recover
- **Human-in-the-Loop:** Approval workflows for sensitive operations
- **CI/CD Integration:** GitHub Actions and Azure DevOps pipeline support

### Hosting Options

- **ASP.NET Web APIs** - Familiar .NET hosting patterns
- **Azure AI Foundry** - Enterprise-grade cloud hosting
- **Container Deployment** - Docker and Kubernetes support
- **On-premises** - Self-hosted deployment options

## 🧪 Examples & Samples

### Python Samples

- [Getting Started with Agents](https://github.com/microsoft/agent-framework/blob/main/python/samples/getting_started/agents) - Basic agent creation and tool usage
- [Getting Started with Workflows](https://github.com/microsoft/agent-framework/blob/main/python/samples/getting_started/workflows) - Basic workflow creation
- [Chat Client Examples](https://github.com/microsoft/agent-framework/blob/main/python/samples/getting_started/chat_client) - Direct chat client usage patterns
- [Observability Examples](https://github.com/microsoft/agent-framework/blob/main/python/samples/getting_started/observability) - Monitoring and tracing
- [Middleware Examples](https://github.com/microsoft/agent-framework/blob/main/python/samples/getting_started/middleware) - Custom middleware implementations

### .NET Samples

- [Getting Started with Agents](https://github.com/microsoft/agent-framework/blob/main/dotnet/samples/GettingStarted/Agents) - Basic agent creation and tool usage
- [Agent Provider Samples](https://github.com/microsoft/agent-framework/blob/main/dotnet/samples/GettingStarted/AgentProviders) - Different agent providers
- [Workflow Samples](https://github.com/microsoft/agent-framework/blob/main/dotnet/samples/GettingStarted/Workflows) - Advanced multi-agent patterns
- [OpenTelemetry Integration](https://github.com/microsoft/agent-framework/blob/main/dotnet/samples/GettingStarted/AgentOpenTelemetry) - Telemetry and monitoring
- [Middleware Examples](https://github.com/microsoft/agent-framework/blob/main/dotnet/samples/GettingStarted/Agents/Agent_Step14_Middleware) - Custom middleware

## 🛠️ Tools & Frameworks

### Development Tools

- **DevUI** - Interactive developer UI for agent development, testing, and debugging workflows
- **VS Code AI Toolkit** - Streamlined experience for building with Microsoft Agent Framework
- **AF Labs** - Experimental packages for cutting-edge features including benchmarking and reinforcement learning

### Integration Options

- **Model Context Protocol (MCP)** - Connect to external tools and data servers
- **Agent-to-Agent (A2A)** - Cross-runtime agent collaboration
- **OpenAPI Integration** - Automatic tool generation from REST APIs
- **Azure Logic Apps** - Enterprise system connectors

## 📊 Monitoring & Observability

### Telemetry & Monitoring

- **OpenTelemetry Integration** - Built-in distributed tracing and metrics
- **Azure Monitor** - Enterprise monitoring and alerting
- **Application Insights** - Deep application performance monitoring
- **Aspire Dashboard** - Development-time observability
- **Custom Dashboards** - Grafana and other visualization platforms

### Key Metrics

- **Conversation Flows** - Visualize message flows between agents
- **Model Usage** - Track token consumption and costs
- **Performance Metrics** - Monitor response times and throughput
- **Error Tracking** - Identify and debug issues

## 🔗 Related Technologies

### Microsoft AI Ecosystem

- **Semantic Kernel** - Predecessor framework for AI orchestration
- **AutoGen** - Multi-agent conversation framework
- **Azure AI Foundry** - Cloud platform for AI development
- **Microsoft 365 Agents SDK** - Enterprise agent development
- **Copilot Studio** - Low-code agent development

### Standards & Protocols

- **Model Context Protocol (MCP)** - Standard for tool integration
- **OpenAPI** - API specification standard
- **OpenTelemetry** - Observability standard
- **Azure AI Content Safety** - Content moderation and safety

## 🤝 Contributing

We welcome contributions to this awesome list!

### Quick Contribution Guide

1. Test your contributions thoroughly
2. Update the appropriate README section
3. Submit a pull request with a clear description

### Contributing to Microsoft Agent Framework

- For bugs or issues with Microsoft Agent Framework, file a [GitHub issue](https://github.com/microsoft/agent-framework/issues)
- Join the [Azure AI Foundry Discord](https://discord.gg/b5zjErwbQM) community
- Check out the [Contributing Guide](https://github.com/microsoft/agent-framework/blob/main/CONTRIBUTING.md)

## 📄 License

This project is licensed under the CC0 License - see the [LICENSE](LICENSE) file for details.

Microsoft Agent Framework is licensed under the [MIT License](https://github.com/microsoft/agent-framework/blob/main/LICENSE).

---

**Note:** Microsoft Agent Framework is currently in public preview. Please submit feedback or issues on the [GitHub repository](https://github.com/microsoft/agent-framework).

## ™️ Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
