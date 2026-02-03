# Enterpret Content Studio

A Claude Code plugin for creating, editing, and publishing marketing and thought leadership content for Enterpret.

## Features

- **SEO Content Track**: Streamlined workflow for keyword-targeted blog posts and how-to guides
- **Thought Leadership Track**: Full workflow for opinion pieces, executive bylines, and customer stories
- **Web & Desk Research**: Industry trends, data, and credible source finding
- **Customer Feedback Research**: Integration with Wisdom MCP for customer quotes and insights
- **SEO Optimization**: Complete guide for search engine optimization
- **Citation Verification**: Source validation and credibility checking
- **Copyediting & Polish**: AI slop removal and prose enhancement
- **Brand Voice Alignment**: Enterpret-specific tone and messaging guidelines

## Content Types Supported

- Blog posts & articles
- Case studies & customer stories
- LinkedIn posts (company + executive)
- Social media content
- Content briefs

## Installation

### Prerequisites

- Claude Code CLI installed
- Access to Enterpret's Wisdom MCP server (for customer feedback research)

### Install from GitHub

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/enterpret-content-studio-plugin.git

# Navigate to your Claude skills directory
cd ~/.claude/skills

# Copy or symlink the plugin
cp -r /path/to/enterpret-content-studio-plugin ./enterpret-content-studio

# Or create a symlink for easier updates
ln -s /path/to/enterpret-content-studio-plugin ./enterpret-content-studio
```

### Install from ZIP

1. Download the latest release ZIP file
2. Extract to your Claude skills directory:
   ```bash
   unzip enterpret-content-studio-v5.zip -d ~/.claude/skills/
   ```
3. Restart Claude Code or reload skills

## Usage

The plugin automatically triggers when you mention content-related keywords:

**Trigger phrases**: blog post, article, case study, customer story, LinkedIn post, social media, thought leadership, content brief, marketing content, ghostwriting, SEO, copyedit, edit, proofread, citations, research

### Quick Start Examples

**SEO blog post:**
```
Write an SEO blog post about [topic] targeting the keyword "[keyword]"
```

**Thought leadership:**
```
Draft a thought leadership piece on [topic] for Varun's LinkedIn
```

**Customer story:**
```
Create a customer story for [company] about [use case]
```

**Edit existing content:**
```
Copyedit this draft: [paste content]
```

**Research:**
```
Research industry trends on [topic] with credible sources
Find customer quotes about [topic] using Wisdom
```

## Workflows

### SEO Content Track (4 steps)
1. Keyword & Intent
2. Research
3. Draft
4. Optimize & Polish

### Thought Leadership Track (10 steps)
1. Clarify Brief
2. Web/Desk Research
3. Customer Research
4. Brainstorm Narrative Spines
5. Draft Content
6. Apply Brand Voice
7. Optimize
8. Verify Sources
9. Prepare for Review
10. Revise & Finalize

## Reference Documentation

The plugin includes comprehensive guides:

- `references/templates.md` - Content templates for all formats
- `references/brand-voice.md` - Enterpret brand voice and messaging
- `references/writing-samples.md` - Real Enterpret content examples
- `references/research-guide.md` - Web and desk research methodology
- `references/wisdom-mcp.md` - Customer feedback research guide
- `references/seo-guide.md` - SEO optimization checklist
- `references/citations-guide.md` - Source verification standards
- `references/copyediting-guide.md` - Prose polish and AI slop removal
- `references/review-workflow.md` - Content review preparation

## Requirements

- Claude Code (latest version recommended)
- Optional: Wisdom MCP server for customer feedback research

## License

Internal Enterpret use only.

## Support

For questions or issues, contact the Enterpret content team or file an issue in this repository.

## Version

v5 - Released February 2026
