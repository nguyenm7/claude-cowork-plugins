# Claude Cowork Plugins

A collection of Claude Code plugins for enhanced productivity and specialized workflows.

## Available Plugins

### 🎨 [Enterpret Content Studio](./plugins/enterpret-content-studio)

Content production plugin for creating, editing, and publishing marketing and thought leadership content.

**Features:**
- SEO content workflows
- Thought leadership writing
- Customer feedback research (Wisdom MCP integration)
- SEO optimization & citation verification
- Copyediting & brand voice alignment

**Use cases:** Blog posts, case studies, LinkedIn posts, social media content, content briefs

---

## Installation

### Quick Install (Recommended)

Install individual plugins directly into your Claude skills directory:

```bash
# Navigate to your Claude skills directory
cd ~/.claude/skills

# Clone this repository
git clone https://github.com/aavaz-ai/claude-cowork-plugins.git

# Symlink the plugin you want
ln -s ~/absolute/path/to/claude-cowork-plugins/plugins/enterpret-content-studio ./enterpret-content-studio

# Or copy it
cp -r claude-cowork-plugins/plugins/enterpret-content-studio ./enterpret-content-studio
```

### Install Specific Plugin

```bash
# Clone the repo
git clone https://github.com/aavaz-ai/claude-cowork-plugins.git

# Copy just the plugin you need
cp -r claude-cowork-plugins/plugins/enterpret-content-studio ~/.claude/skills/
```

### Install from ZIP

1. Download the repository as ZIP from GitHub
2. Extract the ZIP file
3. Copy the specific plugin folder from `plugins/` to `~/.claude/skills/`:
   ```bash
   cp -r claude-cowork-plugins/plugins/enterpret-content-studio ~/.claude/skills/
   ```

### Verify Installation

```bash
# List your installed skills
ls ~/.claude/skills/

# You should see the plugin directory
# enterpret-content-studio/
```

Restart Claude Code or reload skills to activate.

## Usage

Each plugin has its own documentation in its respective directory. See individual plugin READMEs for:
- Trigger phrases
- Workflow guides
- Feature documentation
- Examples

## Plugin Structure

```
claude-cowork-plugins/
├── README.md                          # This file
└── plugins/
    └── enterpret-content-studio/      # Individual plugin
        ├── README.md                  # Plugin-specific docs
        ├── SKILL.md                   # Claude skill definition
        ├── references/                # Reference materials
        ├── scripts/                   # Helper scripts
        └── assets/                    # Assets
```

## Contributing

To add a new plugin to this repository:

1. Create a new directory under `plugins/`
2. Include a `SKILL.md` file (required by Claude Code)
3. Add a `README.md` with installation and usage instructions
4. Submit a pull request

## Requirements

- Claude Code CLI (latest version recommended)
- Access to any MCP servers required by specific plugins

## License

Individual plugins may have different licenses. See each plugin's directory for details.

## Support

For plugin-specific issues, see the individual plugin's README. For general repository questions, file an issue in this repository.

## Version

Last updated: February 2026
