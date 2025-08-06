# 🧜‍♀️ Claude to Mermaid Integration

**Automated Mermaid diagram generation and publishing powered by Claude Code**

[![Repository](https://img.shields.io/badge/Repository-ClaudetoMermaid-blue)](https://github.com/citizenscolumn/ClaudetoMermaid)
[![Projects](https://img.shields.io/badge/Projects-4-green)](#projects)
[![Diagrams](https://img.shields.io/badge/Diagrams-65-orange)](#diagrams)
[![Dashboard](https://img.shields.io/badge/Dashboard-Live-purple)](https://citizenscolumn.github.io/ClaudetoMermaid/dashboard/)

## 🚀 Overview

This repository demonstrates the integration between **Claude Code** and **Mermaid** for automated diagram generation and publishing. It showcases how AI-powered development can create professional architectural diagrams, workflows, and documentation.

## ✨ Features

- **🤖 AI-Powered Generation**: Diagrams created through Claude Code conversations
- **📊 Interactive Dashboard**: Browse and search all diagrams with a beautiful web interface  
- **🔗 Mermaid.live Integration**: One-click editing for every diagram
- **🌐 GitHub Pages Ready**: Public dashboard for sharing diagram collections
- **📱 Mobile Responsive**: Perfect viewing experience on all devices
- **🔄 Automated Publishing**: Streamlined workflow from creation to publication

## 📊 Live Dashboard

**🌐 [View Interactive Dashboard](https://citizenscolumn.github.io/ClaudetoMermaid/dashboard/)**

The dashboard provides:
- Visual previews of all diagrams
- Search and filtering capabilities  
- Direct links to edit diagrams on Mermaid.live
- GitHub integration for viewing source files
- Mobile-responsive design

## 📁 Projects

### 1. [Claude Integration](projects/claude-integration/)
**Complete Claude Code ecosystem diagrams showing MCP integration, workflows, and architecture**
- 📊 21 diagram files
- 🎨 Multiple formats (SVG, PNG, source)
- 🔗 [View on GitHub](projects/claude-integration/) • [Browse Diagrams](projects/claude-integration/diagrams/) • [Edit Sources](projects/claude-integration/source/)

### 2. [examples](projects/examples/)
**Sample diagrams demonstrating various Mermaid diagram types and use cases**
- 📊 18 diagram files
- 🎨 Multiple formats (SVG, PNG, source)
- 🔗 [View on GitHub](projects/examples/) • [Browse Diagrams](projects/examples/diagrams/) • [Edit Sources](projects/examples/source/)

### 3. [templates](projects/templates/)
**templates diagram collection**
- 📊 8 diagram files
- 🎨 Multiple formats (SVG, PNG, source)
- 🔗 [View on GitHub](projects/templates/) • [Browse Diagrams](projects/templates/diagrams/) • [Edit Sources](projects/templates/source/)

### 4. [Main Diagrams](projects/main-diagrams/)
**Primary diagram collection with core architectural and workflow visualizations**
- 📊 18 diagram files
- 🎨 Multiple formats (SVG, PNG, source)
- 🔗 [View on GitHub](projects/main-diagrams/) • [Browse Diagrams](projects/main-diagrams/diagrams/) • [Edit Sources](projects/main-diagrams/source/)



## 🛠️ How It Works

### 1. Claude Code Integration
```bash
# Generate diagrams using Claude Code + Mermaid CLI
python3 mermaid_integration.py samples

# Create specific project diagrams  
python3 mermaid_examples.py
```

### 2. Automated Publishing
```bash  
# Publish to this repository
python3 mermaid_to_github_workflow.py --username citizenscolumn --repo ClaudetoMermaid
```

### 3. Interactive Dashboard
The system automatically generates a responsive HTML dashboard that provides:
- Project organization with visual cards
- Search functionality across all diagrams
- Filter by diagram type (flowchart, sequence, architecture, etc.)
- Direct integration with Mermaid.live for editing

## 🎯 Key Technologies

- **[Claude Code](https://claude.ai/code)**: AI-powered development environment
- **[Mermaid](https://mermaid.js.org/)**: Diagram generation from text
- **[Mermaid CLI](https://github.com/mermaid-js/mermaid-cli)**: Command-line diagram generation
- **GitHub Pages**: Static site hosting for the dashboard
- **GitHub Actions**: Automated publishing workflows

## 📂 Repository Structure

```
ClaudetoMermaid/
├── README.md                    # This file
├── dashboard/                   # Interactive web dashboard
│   └── index.html              # Main dashboard interface
├── projects/                    # Organized diagram projects
│   ├── claude-integration/      # Claude Code integration examples
│   ├── examples/               # Sample diagrams and workflows  
│   └── main-diagrams/          # Primary diagram collection
├── scripts/                    # Automation and publishing tools
├── .github/                    # GitHub Actions workflows
└── docs/                       # Additional documentation
```

## 🎨 Diagram Types

This repository showcases various Mermaid diagram types:

- **🏗️ Architecture Diagrams**: System overviews and component relationships
- **🔄 Workflow Diagrams**: Process flows and automation sequences  
- **📊 Sequence Diagrams**: Interaction patterns and API flows
- **🌊 Flowcharts**: Decision trees and logic flows
- **📈 Performance Dashboards**: Metrics and monitoring visualizations

## 🔧 Development Workflow

### Creating New Diagrams
1. Use Claude Code to describe the diagram you want
2. Generate using the Mermaid integration tools
3. Preview locally using the dashboard
4. Publish to the repository using automated workflows

### Editing Existing Diagrams
1. Use the dashboard "Edit" links to open diagrams in Mermaid.live
2. Make changes in the live editor
3. Copy updated code back to source files
4. Re-run the publishing workflow

## 📈 Usage Statistics

| Metric | Value |
|--------|--------|
| Total Projects | 4 |
| Total Diagrams | 65 |
| Dashboard Views | [View GitHub Insights](https://github.com/citizenscolumn/ClaudetoMermaid/pulse) |
| Repository Stars | [![GitHub stars](https://img.shields.io/github/stars/citizenscolumn/ClaudetoMermaid)](https://github.com/citizenscolumn/ClaudetoMermaid/stargazers) |

## 🤝 Contributing

This repository serves as a demonstration of Claude Code + Mermaid integration. Contributions welcome:

1. **Fork the repository**
2. **Create new diagram examples** 
3. **Improve the automation scripts**
4. **Enhance the dashboard interface**
5. **Submit pull requests**

## 🎓 Learn More

- **[Mermaid Documentation](https://mermaid.js.org/)**: Complete guide to Mermaid syntax
- **[Claude Code](https://claude.ai/code)**: AI-powered development environment
- **[GitHub Pages](https://pages.github.com/)**: Static site hosting
- **[Repository Issues](https://github.com/citizenscolumn/ClaudetoMermaid/issues)**: Ask questions or report issues

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Anthropic** for Claude Code and AI-powered development tools
- **Mermaid.js Team** for the excellent diagramming library  
- **GitHub** for hosting and Pages functionality
- **Open Source Community** for inspiration and collaboration

---

**🎉 Explore the interactive dashboard and see AI-powered diagram generation in action!**

**Dashboard**: https://citizenscolumn.github.io/ClaudetoMermaid/dashboard/  
**Repository**: https://github.com/citizenscolumn/ClaudetoMermaid

*Last updated: 2025-08-06 09:12:47 - Generated by Claude Code*
