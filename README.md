# Wippy Runtime

Wippy Runtime is a specialized server-side binary that provides AI agent collaboration capabilities. Run multi-agent AI workflows locally with full privacy and control over your data. The platform evolves with your needs - agents can enhance capabilities and create new tools with your approval, building a personalized AI environment that grows more powerful over time.

## Quick Start

1. **Download** the latest release for your platform from the releases page
2. **Extract** the archive to your desired location
3. **Run** the server binary and configure your API keys when prompted

## Downloads

### Wippy Runtime

- **Windows AMD64**: wippy-windows-amd64-{version}.zip
- **Linux AMD64**: wippy-linux-amd64-{version}.tar.gz
- **Linux ARM64**: wippy-linux-arm64-{version}.tar.gz
- **macOS AMD64**: wippy-darwin-amd64-{version}.tar.gz
- **macOS ARM64**: wippy-darwin-arm64-{version}.tar.gz

### PackCLI Helper Tool

PackCLI helper tool is included within the Wippy Runtime archives.

## Installation

### System Requirements

**Minimum Requirements:**
- 4GB RAM
- 500MB free disk space
- Modern operating system (Windows 10+, macOS 10.15+, Ubuntu 18.04+)

**Recommended Requirements:**
- 8GB RAM
- 1GB free disk space
- SSD storage for better performance

### Step-by-Step Installation

#### Step 1: Download the Release

Visit the [releases page](https://github.com/wippyai/wippy-releases/releases) and download the appropriate archive for your platform.

#### Step 2: Extract the Archive

**Windows:**
```bash
unzip wippy-windows-amd64-{version}.zip
```

**Linux/macOS:**
```bash
tar -xzf wippy-linux-amd64-{version}.tar.gz
# or
tar -xzf wippy-darwin-amd64-{version}.tar.gz
```

#### Step 3: Make Executables (Linux/macOS only)

```bash
chmod +x wippy packcli
```

#### Step 4: Verify Installation

**Windows:**
```bash
wippy.exe --version
packcli.exe --version
```

**Linux/macOS:**
```bash
./wippy --version
./packcli --version
```


## Usage

### Windows
```bash
# Extract the archive
unzip wippy-windows-amd64-{version}.zip

# Run the executable
wippy.exe --help
```

### Linux
```bash
# Extract the archive
tar -xzf wippy-linux-amd64-{version}.tar.gz

# Make executable and run
chmod +x wippy
./wippy --help
```

### macOS
```bash
# Extract the archive
tar -xzf wippy-darwin-amd64-{version}.tar.gz

# Make executable and run
chmod +x wippy
./wippy --help
```

## PackCLI Usage

PackCLI is included within the Wippy Runtime archives for module management and development tasks.

### Windows
```bash
# After extracting the archive
packcli.exe --help
packcli.exe module init my-module
```

### Linux
```bash
# After extracting the archive
chmod +x packcli
./packcli --help
./packcli module init my-module
```

### macOS
```bash
# After extracting the archive
chmod +x packcli
./packcli --help
./packcli module init my-module
```

## Features

### Core Architecture

#### AI Agent Framework
- **Multi-agent Coordination**: Specialized agents working together with defined roles
- **Intelligent Task Delegation**: Automatic assignment of tasks to the most suitable agent
- **Persistent Conversations**: Context preservation across multiple sessions
- **Dynamic Agent Selection**: Automatic agent selection based on task requirements
- **Runtime Code Modification**: Agents can enhance capabilities and create new tools with user approval

#### Local Operation & Privacy
- **Complete Privacy**: All data stays on your machine - no cloud storage required
- **Local SQLite Database**: All data stored locally for complete control
- **Offline Capabilities**: Knowledge base operations work without internet
- **No Telemetry**: Zero data collection or usage statistics
- **Encrypted Storage**: API keys and sensitive data encrypted locally

### Knowledge Management

#### Document Processing
- **File Upload Support**: PDF, Word, PowerPoint, images (JPG, PNG, GIF), and text files
- **Local Knowledge Bases**: Document storage and retrieval without external services
- **Searchable Content**: Full-text search across all uploaded documents
- **Cross-session Persistence**: Information remains available across multiple work sessions
- **Content Processing**: Automatic extraction and indexing of document content

#### Information Retrieval
- **Intelligent Search**: Context-aware search across knowledge bases
- **Agent Access Control**: Authorized agents can access specific knowledge bases
- **Real-time Updates**: Immediate availability of newly uploaded content
- **Metadata Extraction**: Automatic categorization and tagging of documents

### Project Organization

#### Workflow Management
- **Structured Workflows**: Organized approach to complex multi-step tasks
- **Project Templates**: Pre-configured agent teams for common use cases
- **Session Continuity**: Work continues seamlessly across multiple sessions
- **Progress Tracking**: Visual progress indicators and milestone management
- **Task Dependencies**: Complex task chains with automatic dependency resolution

#### Collaboration Features
- **Agent Communication**: Seamless information sharing between agents
- **Workflow Coordination**: Synchronized execution of multi-agent tasks
- **Result Aggregation**: Automatic compilation of results from multiple agents
- **Quality Assurance**: Built-in validation and error checking

### System Integration

#### External Connections
- **API Integrations**: Connect to external services and APIs
- **OAuth Support**: Secure authentication with external platforms
- **Credential Management**: Secure storage and management of API keys
- **Real-time Synchronization**: Live data updates from connected services

#### Extensibility
- **Plugin Architecture**: Add new capabilities through modular plugins
- **Custom Tools**: Create specialized tools for specific workflows
- **MCP Support**: Model Context Protocol integration
- **Workflow Automation**: Automated execution of complex processes

### Development Tools

#### PackCLI Integration
- **Module Management**: Create, update, and manage custom modules
- **Development Workflow**: Streamlined development and testing process
- **Package Creation**: Build and distribute custom packages
- **Version Control**: Track changes and manage module versions

#### Runtime Enhancement
- **Hot Reloading**: Update code without restarting the server
- **Dynamic Module Loading**: Add functionality at runtime
- **Custom Agent Creation**: Develop specialized agents for specific tasks
- **Tool Development**: Create custom tools and utilities

### Platform Capabilities

#### Multi-Platform Support
- **Cross-Platform**: Windows, macOS, and Linux support
- **Architecture Support**: AMD64 and ARM64 architectures
- **Consistent Experience**: Same functionality across all platforms
- **Platform-Specific Optimizations**: Optimized for each operating system

#### Performance Features
- **Efficient Resource Usage**: Optimized memory and CPU utilization
- **Fast Startup**: Quick server launch and initialization
- **Responsive Processing**: Smooth operation even with complex workflows
- **Background Processing**: Non-blocking execution of long-running tasks

### Security & Compliance

#### Data Protection
- **Local Storage Only**: No data leaves your machine
- **Encryption**: Sensitive data encrypted at rest
- **Access Control**: Granular permissions for different agents
- **Audit Trail**: Complete logging of all operations

#### Privacy Features
- **No Cloud Dependencies**: Complete local operation
- **Zero Data Collection**: No usage analytics or telemetry
- **API Key Protection**: Secure storage of authentication credentials
- **Isolated Execution**: Agents run in controlled environments

### Use Cases

#### Personal Productivity
- **Document Analysis**: Process and analyze large document collections
- **Research Assistance**: Multi-agent research workflows
- **Content Creation**: Collaborative content generation
- **Task Automation**: Automate repetitive workflows

#### Professional Development
- **Code Analysis**: Multi-agent code review and optimization
- **Project Management**: Coordinated project execution
- **Quality Assurance**: Automated testing and validation
- **Documentation**: Automated documentation generation

#### Business Applications
- **Data Processing**: Multi-step data analysis workflows
- **Report Generation**: Automated report creation and analysis
- **Customer Support**: AI-powered support workflows
- **Process Optimization**: Continuous improvement of business processes

## Archive Format

All releases are distributed as compressed archives:
- **Windows**: ZIP format (.zip)
- **Linux/macOS**: GZIP-compressed TAR format (.tar.gz)

## Verification

SHA256 checksums are available for each release archive.

## Troubleshooting

### Common Issues

#### Permission Denied (Linux/macOS)
```bash
# Make sure files are executable
chmod +x wippy packcli
```

#### Archive Extraction Issues
- Ensure you have sufficient disk space
- Verify the download completed successfully
- Check SHA256 checksums if available

#### API Connection Issues
- Verify your API keys are correct
- Check your internet connection
- Ensure you have sufficient API credits

### Getting Help

- Check the FAQ section below for common questions
- Visit the [Issues page](https://github.com/wippyai/wippy-releases/issues) for bug reports
- Contact Spiral Scout for commercial support

## Updates & Maintenance

Wippy automatically checks for updates on startup and installs modular updates. Your server state and custom builds remain unchanged.

### How Updates Work

Updates are handled automatically when you start the server. The system will:
- Check for available updates
- Download and install new modules
- Preserve your data and customizations
- Notify you of any breaking changes

### Uninstallation

To remove Wippy Runtime:

1. Delete the extracted folder
2. Remove any configuration files (usually in `~/.wippy/` or `%APPDATA%/wippy/`)
3. Remove any shortcuts or start menu entries you created

## Frequently Asked Questions

### General Questions

#### What is Wippy Runtime?

Wippy Runtime is a specialized server-side binary that provides a complete AI agent platform designed for local operation. It's an integrated server platform where you can change and replace approximately 99% of the server codebase from inside Wippy itself at runtime. It's a complete server operating system designed for AI agents to live, develop, and improve within a unified system.

#### How is this different from the main Wippy Local?

This is a specialized runtime version optimized for specific use cases and deployment scenarios. While maintaining the core functionality of the main Wippy Local platform, this version focuses on streamlined operation and specialized workflows.

#### Can Wippy Runtime work completely locally?

Yes, Wippy Runtime can work completely locally on your machine. When working locally, Wippy does not collect any information or statistics from your installation. All your data remains on your computer, and no data is sent to external servers except for AI model API calls.

### Technical Questions

#### Do I need to know programming to use Wippy Runtime?

You don't need to be a programmer to work with Wippy Runtime, but having a structured approach is helpful. Wippy is designed to be accessible to non-technical users through its AI agent capabilities, while also providing powerful development tools for advanced users.

#### What file types does Wippy Runtime support?

Wippy Runtime supports:
- **Documents**: PDF, Word, PowerPoint
- **Images**: JPG, PNG, GIF
- **Text files**: Plain text, markdown, and other text formats
- **Data files**: CSV, JSON, XML

Document processing happens locally, and all content is stored in your local knowledge base.

#### What makes Wippy Runtime different from other AI frameworks?

Wippy Runtime is not just a server framework - it's a fully integrated server operating system designed for agents to live, develop, and improve within a unified system. All of this runs within a single binary. The closest comparison would be a mix between BabyAGI and Erlang OTP, specifically designed for AI agents with a governance pipeline on top.

#### How do I start using Wippy Runtime effectively?

Start small with simple tasks. Begin by exploring the server capabilities and uploading your first file or creating a basic project. Don't try to handle complex projects all at once - use an iterative approach starting with a research phase and testing connections step by step.

### Installation & Setup

#### Do I need both OpenRouter and OpenAI API keys?

- **OpenRouter API key**: Required for basic functionality
- **OpenAI API key**: Optional but recommended for knowledge base embeddings and advanced features

Wippy is provider-agnostic. Use OpenRouter if you like, or plug in Anthropic, OpenAI, or local models. You can change providers per environment or workflow.

#### Can I use Wippy Runtime without internet?

Wippy Runtime can work offline for most operations, but you'll need internet access for:
- AI model API calls
- Initial setup and configuration
- Updating modules and components

All your data and knowledge bases work completely offline.

### Features & Capabilities

#### Can Wippy Runtime integrate with external services?

Wippy Runtime connects to LLM model providers based on your configuration and can integrate with anything that has an API or create APIs for other platforms to connect to it. We provide modules for Discord, Slack, and other integrations in future releases.

#### How does the multi-agent system work?

Wippy Runtime uses specialized AI agents that can:
- Work together on complex tasks
- Automatically delegate subtasks to the most suitable agent
- Maintain context across multiple interactions
- Learn and improve their capabilities over time

#### What is PackCLI and how do I use it?

PackCLI is a helper tool included with Wippy Runtime for:
- Module management and development
- Creating custom packages
- Managing project dependencies
- Building and distributing custom components

### Troubleshooting

#### Wippy Runtime won't start. What should I do?

1. Check that you have sufficient disk space
2. Verify your system meets the minimum requirements
3. Ensure the executable has proper permissions (Linux/macOS)
4. Check the logs for specific error messages
5. Try running from command line to see detailed error output

#### My API keys aren't working. How do I fix this?

1. Verify your API keys are correct and active
2. Check that you have sufficient API credits
3. Ensure your internet connection is working
4. Try regenerating your API keys
5. Check for any rate limiting or usage restrictions

#### How do I reset Wippy Runtime to factory settings?

1. Stop Wippy Runtime completely
2. Delete the configuration directory:
   - **Windows**: `%APPDATA%/wippy/`
   - **macOS**: `~/.wippy/`
   - **Linux**: `~/.wippy/`
3. Restart Wippy Runtime and go through initial setup

### Commercial Use

#### Is Wippy Runtime scalable for team use?

While this build is intended for personal use on your personal machine, the same agent architecture is used in production for multiple organizations. If you're interested in team-based or commercial use of Wippy, please contact Spiral Scout.

#### Can I use Wippy Runtime for commercial purposes?

Wippy Runtime is released under the Apache 2.0 License, which allows commercial use. However, for enterprise deployments or team-based usage, we recommend contacting Spiral Scout for proper licensing and support.

#### Where can I get commercial support?

For commercial support, enterprise features, or team deployments, please contact Spiral Scout through their official channels.

## Security Notes

- Wippy operates completely locally - no data is sent to external servers except for AI model API calls
- All your data remains on your computer
- API keys are stored locally and encrypted
- No telemetry or usage statistics are collected

## License

Wippy Runtime is released under the Apache 2.0 License.

## Maintained By

Wippy is maintained by Spiral Scout.

---

*This documentation is based on the core Wippy Local platform with adaptations for the specialized runtime version.*