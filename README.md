# Awesome Claude Agents 🚀 & MCP Servers - Complete Directory (2025)

A community-driven collection of **Claude Code agents**, sub-agents, and **MCP Servers**—turn your Claude instance into an unstoppable team of domain experts! This repo catalogs plug-and-play agents, agent frameworks, and orchestration recipes contributed by the community.

The Claude Code agent ecosystem has exploded with specialized sub-agents and Model Context Protocol (MCP) servers. Here's the most comprehensive directory of all available resources.

### What are Claude Agents?

**Claude Agents** are specialized, task-focused AI "teammates" defined via simple Markdown+YAML files. Each agent lives in `.claude/agents/` and is scoped with a clear role, tool set, and behaviour prompt. With sub-agent support, Claude Code can now delegate complex projects to expert agents who work in parallel.

## 🌟 Featured Agent Collections (Sub-Agents)

### **Production-Ready & Massive Collections**

| Repository | Agents | Description |
|---|---|---|
| **[VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents)** | 100+ | 🌟 **The Definitive Collection**. Full-stack, DevOps, Data Science, and Business Operations. Formerly `0xfurai`. |
| **[davepoon/claude-code-subagents-collection](https://github.com/davepoon/claude-code-subagents-collection)** | 43+ | **[BuildWithClaude.com](https://www.buildwithclaude.com)**. Includes a CLI tool (`bwc-cli`) and Web UI for easy installation. |
| **[wshobson/agents](https://github.com/wshobson/agents)** | 48+ | Production-ready specialists with orchestration patterns and advanced workflows. |
| **[lodetomasi/agents-claude-code](https://github.com/lodetomasi/agents-claude-code)** | 100 | "Elite Claude Agents" - Transform Claude into a personal tech army (React, AWS, K8s, ML). |

### **Specialized & Community Collections**

| Repository | Focus |
|---|---|
| **[derek-opdee/subagent-example-script](https://github.com/derek-opdee/subagent-example-script)** | Powerful orchestration commands: Tech Debt Finder, Architecture Reviewer, Test Generator. |
| **[vijaythecoder/awesome-claude-agents](https://github.com/vijaythecoder/awesome-claude-agents)** | AI development team structure with Tech Lead, Analyst, and domain experts. |
| **[charles-adedotun/claude-code-sub-agents](https://github.com/charles-adedotun/claude-code-sub-agents)** | Minimal AI agent system. "One agent to rule them all" - bootstraps project-specific agents. |
| **[valllabh/claude-agents](https://github.com/valllabh/claude-agents)** | Enhanced agents with interactive workflows (Analyst, Scrum Master, QA Engineer). |
| **[lst97/claude-code-sub-agents](https://github.com/lst97/claude-code-sub-agents)** | Personal use full-stack development agents (Frontend, Backend, Mobile). |

## 🔌 Model Context Protocol (MCP) Servers

The **Model Context Protocol (MCP)** allows Claude to connect to external data and tools.

### **The Master List**
**[punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)** - 🌟 **76k+ Stars**. The definitive directory of MCP servers.
*   **Databases**: PostgreSQL, MySQL, SQLite, MongoDB, Snowflake...
*   **Cloud**: AWS, Cloudflare, Kubernetes, Docker...
*   **Dev Tools**: GitHub, GitLab, Sentry, Postman...
*   **Productivity**: Google Drive, Slack, Notion, Obsidian...

### **Featured MCP Repos**
*   **[modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)**: Official reference implementations from the MCP team.
*   **[github/github-mcp-server](https://github.com/github/github-mcp-server)**: Official GitHub integration for repository management.

## 📚 Guides & Resources

| Repository | Focus |
|---|---|
| **[wesammustafa/Claude-Code-Everything-You-Need-to-Know](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know)** | **Ultimate Guide**: Setup, Prompts, Commands, Hooks, Workflows, and the BMAD Method. |
| **[alvinunreal/awesome-claude](https://github.com/alvinunreal/awesome-claude)** | Curated list of ALL things Claude (Models, Tools, Agents, Prompts). |

## 🛠️ Installation & Setup

### **CLI Tools**
Some collections offer CLI tools to make installation easier:

**Dave Poon's Collection (bwc-cli):**
```bash
npm install -g bwc-cli
bwc init
bwc add --agent python-pro
```

**Valllabh's Collection:**
```bash
curl -fsSL https://raw.githubusercontent.com/valllabh/claude-agents/main/install-agents.sh | bash -s -- --from-github
```

### **Manual Installation**
1.  Create the agents directory: `mkdir -p .claude/agents`
2.  Copy agent markdown files (e.g., `code-reviewer.md`) into `.claude/agents/`.
3.  Invoke in Claude Code: "Use the code-reviewer agent to..."

## 🏗️ Agent Categories & Use Cases

### **Development Lifecycle**
*   **Planning**: Requirements analyst, architect, tech lead.
*   **Implementation**: Backend/frontend developers, API designers.
*   **Quality**: Code reviewers, testers, security auditors.
*   **Operations**: DevOps engineers, deployment specialists.

### **Domain Specialists**
*   **Languages**: Python, JavaScript, TypeScript, Go, Rust, Java.
*   **Frameworks**: React, Vue, Django, FastAPI, Spring Boot.
*   **Cloud**: AWS, GCP, Azure, Kubernetes.

## 🤝 Contributing

*   Fork this repo, add your `my-unique-agent.md` files to the main directory, and open a PR.
*   Include a short description and a working example in each agent file.
*   Want your own agent repo included? Submit a link and summary via PR or issue.

## License

MIT License for this directory. Individual agent files may contain separate copyright/attribution info.

## Credits

Big thanks to the community builders:
*   [VoltAgent](https://github.com/VoltAgent)
*   [Dave Poon](https://github.com/davepoon)
*   [W. Shobson](https://github.com/wshobson)
*   [Lorenzo De Tomasi](https://github.com/lodetomasi)
*   [Derek Opdee](https://github.com/derek-opdee)
*   [Punkpeye](https://github.com/punkpeye)

> “The most powerful Claude agents feel like hiring a team of experts—but you get code reviews, migrations, and tests done in minutes.”

*Happy hacking! Add, remix, and power up your Claude!*
