# Agent Dev Suite

Complete Ubuntu/Debian development environment setup with AI-assisted workflows and agent-driven development.

## 🚀 Quick Start

### For Development Environment Setup:
```bash
git clone https://github.com/your-repo/agent-dev-suite.git
cd agent-dev-suite/tools
chmod +x dev_tools_menu.sh && ./dev_tools_menu.sh
```
- ⭐ **[Star this repo](https://github.com/amrhas82/agent-dev-suite)** to get notified of updates
- 💬 **[Join Discord](https://discord.gg/SDaSrH3J8d)** to get help with your vibecoding struggles

### For AI-Assisted Development:
- **Simple 3-step workflow**: See `ai/simple/`
- **Claude-optimized agents**: See `ai/claude-subagents/`
- **BMAD framework**: See `ai/bmad/`

## 📁 What's Included

### 🤖 AI Workflows (`ai/`)
Four comprehensive approaches to AI-assisted development:

#### Simple Workflow (`ai/simple/`)
- **3-step process**: Create PRD → Generate Tasks → Process Task List
- Perfect for features, small projects, and quick iterations
- Streamlined agent guidance for rapid development

#### Claude Subagents (`ai/claude-subagents/`)
- **BMAD + Simple hybrid**: Optimized mix of BMAD and Simple workflows adapted for Claude
- **Context-optimized**: Compacted to save context while maintaining full functionality
- **Ready-to-deploy**: Entire bundle can be copied directly to `~/.claude`
- **Complete agent ecosystem**: All agents, teams, workflows, and dependencies included

#### BMAD Framework (`ai/bmad/`)
Role-based subagents that can work with CLI, IDE, and web AI agents:

**a. BMAD-Claude (`ai/bmad/bmad-claude/`)**
- Ready-to-use BMAD adapted roles for direct placement under `~/.claude`
- Complete agent teams with all dependency folders included
- Immediate deployment for Claude Code users

**b. BMAD-Core (`ai/bmad/bmad-core/`)**
- Complete dependency folders, scripts, and workflows
- Core framework for BMAD methodology
- Configurable agents and templates for various development scenarios

**c. BMAD-OpenCode (`ai/bmad/bmad-opencode/`)**
- Subagents ready for BMAD integration with OpenCode
- Optimized configurations for OpenCode environment
- Plug-and-play agent definitions

**d. BMB - BMAD Builder (`ai/bmad/bmb/`)**
- Build your own custom subagents
- Agent creation and management workflows
- Modular system for specialized agent development

#### Task Master (`ai/README-task-master.md`)
- **AI-powered task management system** for structured development workflows
- **PRD-to-tasks automation**: Parse requirements into actionable, dependency-aware tasks
- **MCP integration**: Works seamlessly with Cursor, Windsurf, VS Code, Claude Code
- **Smart task expansion**: AI-driven complexity analysis and subtask generation
- **Cross-platform CLI**: Works with multiple AI providers (Claude, GPT, Gemini, Perplexity, etc.)
- **Dependency management**: Automatic task ordering and validation
- Perfect for systematic feature development and maintaining development momentum

### 🛠️ Development Tools (`tools/`)
- **📖 Complete Tools Guide**: [`tools_guide.md`](tools/tools_guide.md) - Comprehensive documentation with examples and quick start commands
- **Automated installation scripts** for Tmux, Neovim, Lite XL
- **Interactive dev tools menu** for easy setup
- **Configuration files** and comprehensive guides
- **AI development utilities** and automation scripts

### 🖥️ Environment Setup (`env/`)

#### System Setup (`env/setup/`)
- **Backup & recovery** with Clonezilla guides
- **Partition management** and recovery procedures
- **System configuration** for optimal development environment
- **Hibernate setup** and power management

#### Development Environments (`env/tools/`)
- **Window managers**: BSPWM, DWM, Openbox configurations
- **Productivity tools**: ButterBash, ButterNotes, ButterScripts
- **Editor setups**: Neovim configuration and plugins
- **Shell environments**: Customized terminal setups

### 🔌 Integrations (`integrations/`)
- **MCP Servers**: [awesome_mcp_servers.md](integrations/awesome_mcp_servers.md) - 200+ comprehensive list of Model Context Protocol servers
- **External tool integrations** for enhanced AI capabilities
- **API connections** and service integrations
- **Extension packs** for specialized development workflows

## 🎯 Use Cases

This suite is designed for developers who want to:

### 🏗️ **Environment Setup**
- Set up a complete Ubuntu/Debian development environment from scratch
- Configure optimal development tools and workflows
- Automate system setup and maintenance tasks

### 🤖 **AI-Driven Development**
- Use AI agents to build features systematically with Task Master
- Implement role-based development workflows (BMAD Framework)
- Leverage specialized AI agents for different development phases
- Parse PRDs into actionable, dependency-aware task lists
- Integrate AI task management directly into your IDE (Cursor, VS Code, Windsurf)

### 🚀 **Productivity Enhancement**
- Streamline development workflows with automation
- Use proven configurations for popular tools
- Integrate AI capabilities into existing workflows

## 📚 Documentation Structure

### Getting Started
- [Quick Start Guide](#-quick-start)
- [Installation Instructions](tools/README.md)
- [Environment Configuration](env/)

### AI Guided Development
- [Simple Workflow Guide](ai/simple/ai_dev_tasks.md)
- [Claude Subagents](ai/claude-subagents/) - BMAD+Simple hybrid optimized for Claude
- [BMAD Framework](ai/bmad/README.md)
  - [BMAD-Claude Agents](ai/bmad/bmad-claude/agents/) - Ready-to-use Claude agents
  - [BMAD-Core Workflows](ai/bmad/bmad-core/workflows/) - Core framework workflows
  - [BMAD-OpenCode Agents](ai/bmad/bmad-opencode/) - Ready-to-use OpenCode agents
  - [BMB Agent Builder](ai/bmad/bmb/workflows/create-agent/) - Create custom agents
- [Task Master](ai/README-task-master.md)

### Tools & Environment
- [Development Tools Guide](tools/guides/)
- [Window Manager Setup](env/tools/README.md)
- [System Administration](env/setup/)

### Integrations
- [MCP Server Integration](integrations/awesome_mcp_servers.md) - 200+ servers
- [External Tool Setup](integrations/README.md)

## 🛡️ System Requirements

- **OS**: Ubuntu 20.04+ or Debian 11+
- **Prerequisites**: `git`, `curl`, `sudo` access
- **Memory**: 4GB+ RAM recommended
- **Storage**: 10GB+ free space
- **Network**: Internet connection for AI services

## 🔄 Workflow Examples

### Simple 3-Step Workflow
```bash
# 1. Create PRD
cd ai/simple
./1-create-prd.md

# 2. Generate Tasks
./2-generate-tasks.md

# 3. Process Task List
./3-process-task-list.md
```

### Claude Subagents (BMAD+Simple Hybrid)
```bash
# Deploy optimized agents to Claude
cp -r ai/claude-subagents/* ~/.claude/
# Ready to use in Claude Code immediately
```

### BMAD Framework
```bash
# Use ready-made Claude agents
cd ai/bmad/bmad-claude
# Copy to ~/.claude for immediate use

# Use ready-made OpenCode agents
cd ai/bmad/bmad-opencode
# See AGENTS.md for setup instructions

# Work with core framework
cd ai/bmad/bmad-core
./user-guide.md

# Build custom agents
cd ai/bmad/bmb
./README.md
```

### Task Master
```bash
# Install globally
npm install -g task-master-ai

# Initialize in your project
task-master init

# Parse PRD and generate tasks
task-master parse-prd scripts/prd.txt

# Get next task and work on it
task-master next

# Or use via MCP in Cursor/VS Code
# See ai/README-task-master.md for setup
```

### Environment Setup
```bash
# Interactive tools setup
cd tools
./dev_tools_menu.sh

# Manual setup
./master_tmux_setup.sh
./master_neovim_setup.sh
```

## 🏗️ Architecture

```
agent-dev-suite/
├── ai/                          # AI workflows and agents
│   ├── simple/                  # 3-step workflow (PRD → Tasks → Process)
│   ├── claude-subagents/        # BMAD+Simple hybrid optimized for Claude
│   ├── bmad/                    # BMAD framework with role-based agents
│   │   ├── bmad-claude/         # Ready-to-use Claude agents
│   │   ├── bmad-core/           # Core framework and dependencies
│   │   ├── bmad-opencode/       # Ready-to-use OpenCode agents
│   │   └── bmb/                 # BMAD Builder for custom agents
│   └── README-task-master.md    # Task Master guide & setup
├── env/                         # Environment configuration
│   ├── setup/                   # System setup
│   └── tools/                   # Development environments
├── tools/                       # Development utilities
├── integrations/                # External integrations (MCP servers)
└── docs/                        # Comprehensive documentation
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 🔗 Related Projects

- [BMAD Framework](https://github.com/bmad-code-org/BMAD-METHOD) - Core AI development framework
- [MCP Protocol](https://modelcontextprotocol.io) - Model Context Protocol specifications
- [Zorin OS Development Environment](https://zorin.com/os/download/) - Ubuntu development setup

## 📊 Project Status

- ✅ **Environment Setup**: Complete with automated scripts
- ✅ **Simple AI Workflow**: Ready for production use
- ✅ **BMAD Framework**: Full implementation with all agents
- ✅ **Task Master**: Integrated with MCP support for all major editors
- ✅ **Integration Support**: MCP servers and external tools
- 🔄 **Documentation**: Continuously improving
- 🚧 **New Features**: Actively developing

## 🆘 Support

### Getting Help
- **Documentation**: Check the relevant section in this README
- **Issues**: [GitHub Issues](https://github.com/your-repo/agent-dev-suite/issues)
- **Discussions**: [GitHub Discussions](https://github.com/your-repo/agent-dev-suite/discussions)

### Common Issues
- **Permission Errors**: Use `sudo` for system-level installations
- **AI Service Limits**: Check API key configurations
- **Environment Conflicts**: Use the provided setup scripts

## 🎉 What's New

### Version 2.0.0
- 🔄 **Reorganized Structure**: New logical folder organization
- 🤖 **Enhanced AI Workflows**: Improved simple and BMAD frameworks
- 🛠️ **Updated Tools**: Latest configurations and automation
- 📚 **Better Documentation**: Comprehensive guides and examples

### Recent Updates
- 🎯 **Task Master Integration**: Full MCP support for Cursor, VS Code, Windsurf, and Claude Code
- 🔌 **MCP Server Integrations**: 200+ servers available
- 🤖 **Enhanced BMAD Framework**: New agents and workflows
- 🛠️ **Improved Environment Setup**: Updated scripts and automation
- 📚 **Comprehensive Documentation**: Streamlined guides and examples

---

**Built with ❤️ for the AI-driven development community**

Transform your development workflow with intelligent automation and AI assistance.