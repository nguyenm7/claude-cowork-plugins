---
name: enterpret-content-studio
description: |
  **Enterpret Content Production Studio**: Create, edit, and publish marketing and thought leadership content for Enterpret.

  MANDATORY TRIGGERS: blog post, article, case study, customer story, LinkedIn post, social media, thought leadership, content brief, content calendar, marketing content, ghostwriting, byline, SEO, copyedit, edit, proofread, citations, sources, customer quotes, feedback quotes, research, industry trends

  Supports: Blog posts & articles, case studies & customer stories, LinkedIn posts (company + executive), social media content, content briefs, web/desk research for industry data, SEO optimization, citation verification, customer feedback research via Wisdom MCP, and prose polish/copyediting.

  Use this skill when anyone at Enterpret needs to create, edit, research, optimize, or review marketing content of any type.
---

# Enterpret Content Studio

Create high-quality marketing and thought leadership content that positions Enterpret as the leader in Customer Intelligence.

---

## Choose Your Workflow

**First, identify the content type:**

| If creating... | Use this track |
|----------------|----------------|
| SEO blog post, keyword-targeted content, how-to guides | → **SEO Track** (streamlined) |
| Thought leadership, opinion pieces, executive bylines, customer stories | → **Thought Leadership Track** (full) |

---

## SEO Content Track (Streamlined)

For keyword-targeted content where structure follows search intent.

### Step 1: Keyword & Intent
- Identify primary keyword and search intent
- Quick SERP analysis: What do top results cover?
- Define target audience and content goal

### Step 2: Research
- Web research for supporting data, stats, examples (`references/research-guide.md`)
- Find credible sources for citations (`references/citations-guide.md`)
- Optional: Customer quotes via Wisdom MCP if relevant

### Step 3: Draft
- Create outline based on SERP expectations and keyword coverage
- Draft content using `references/templates.md` (Blog Post Template)
- Include internal links to related Enterpret content

### Step 4: Optimize & Polish
- SEO optimization: title tag, meta description, headings, keyword placement (`references/seo-guide.md`)
- Copyedit pass: Remove AI slop, tighten prose (`references/copyediting-guide.md`)
- Verify sources are credible and linked
- Prepare for review (`references/review-workflow.md`)

**Total steps: 4** | Skip: Brief clarification, narrative brainstorming, customer research deep-dive

---

## Thought Leadership Track (Full)

For opinion-driven content where narrative arc matters.

### Step 1: Clarify the Brief
- Understand content type, audience, goal, key messages
- Align on voice (company vs. executive byline)
- Define success metrics

### Step 2: Web/Desk Research
- Find industry trends, data, credible sources (`references/research-guide.md`)
- Identify contrarian angles or fresh perspectives

### Step 3: Customer Research
- Use Wisdom MCP for customer quotes and feedback (`references/wisdom-mcp.md`)
- Pull proof points that support the narrative

### Step 4: Brainstorm Narrative Spines
- Propose 3 angles with different emotional arcs
- Recommend one based on audience and goal
- **Wait for user approval before drafting**

### Step 5: Draft Content
- Use appropriate template from `references/templates.md`
- Build around the approved narrative spine

### Step 6: Apply Brand Voice
- Follow `references/brand-voice.md`
- Ensure tone matches channel and author

### Step 7: Optimize
- SEO for blogs (`references/seo-guide.md`)
- Copyedit for prose polish (`references/copyediting-guide.md`)

### Step 8: Verify Sources
- Check citations per `references/citations-guide.md`
- Ensure all stats trace to credible originals

### Step 9: Prepare for Review
- Format for Notion per `references/review-workflow.md`
- Flag questions for reviewer

### Step 10: Revise & Finalize
- Incorporate feedback, final copyedit, publish

**Total steps: 10** | Full process for high-stakes content

---

## Content Types

### Blog Posts & Articles
**When to use**: Thought leadership, product updates, industry insights, SEO content

| Blog Type | Workflow Track |
|-----------|----------------|
| SEO / How-to / Keyword-targeted | SEO Track |
| Thought leadership / Opinion / Byline | Thought Leadership Track |
| Product announcements | SEO Track (unless exec byline) |

See `references/templates.md` → Blog Post Template
See `references/seo-guide.md` for optimization
See `references/writing-samples.md` for real Enterpret examples

### Customer Stories
**When to use**: Showcasing customer success, ROI stories, use case validation

**Scaffolding**: Context → Motivation (Use Cases) → Conclusion

Each use case follows: **Tension → Change → Meaning**

See `references/templates.md` → Customer Story Template

**Research with Wisdom MCP**: Pull customer feedback, quotes, and outcomes from the Knowledge Graph. See `references/wisdom-mcp.md`.

### LinkedIn Posts
**When to use**: Executive thought leadership, company updates, engagement

Two modes:
- **Company page**: Announcements, hiring, customer wins
- **Executive ghostwriting**: Varun, Kevin, other leaders

See `references/templates.md` → LinkedIn Templates

### Social Media (Twitter/X)
**When to use**: Quick insights, threads, engagement
See `references/templates.md` → Social Media section

---

## Specialized Capabilities

### Narrative Spine Brainstorming (Thought Leadership Track Only)

**IMPORTANT**: For thought leadership content, always propose 3 narrative angles and get user approval before drafting. Skip this for SEO content.

After research, brainstorm 3 different spines (emotional arcs) for the content:

**Spine types** (from brand voice):
- **Chaos → Clarity**: Overwhelming problem → organized solution
- **Generic → Specific**: One-size-fits-all fails → tailored approach wins
- **Reactive → Proactive**: After-the-fact reporting → ahead-of-issues intelligence

**Format for presenting options**:
```
## Narrative Options

**Option A: [Spine Name]**
- Hook: [Opening stat or provocative statement]
- Arc: [How the story unfolds]
- Key evidence: [Stats/quotes that support this angle]

**Option B: [Spine Name]**
...

**Option C: [Spine Name]**
...

**Recommendation**: Option [X] because [reason tied to audience/goal]
```

**Wait for user approval** before proceeding to draft.

### Web & Desk Research

Before drafting, research industry trends, data, and credible sources:

1. **Frame research questions** — What do you need to know?
2. **Search credible sources first** — Analysts (Gartner, Forrester), academic (HBR), major press
3. **Validate what you find** — Who produced it? When? Primary source?
4. **Document findings** — Stats, trends, expert quotes, citation URLs

**Search strategy**:
```
[topic] site:gartner.com OR site:mckinsey.com OR site:hbr.org
[topic] survey 2025 OR benchmark report
```

See `references/research-guide.md` for full guide.

### Customer Feedback Research (Wisdom MCP)

Use the Wisdom MCP server to find real customer quotes and insights:

```
search_knowledge_graph: "customers struggling with [topic]"
```

**Use cases**:
- Find quotes to support blog claims
- Research customer pain points for content ideas
- Validate trends with real feedback data
- Pull account-specific feedback for case studies

See `references/wisdom-mcp.md` for full guide.

### SEO Optimization

For blog content targeting organic search:

1. **Before writing**: Research keywords, analyze search intent
2. **While writing**: Optimize title, meta, headings, internal links
3. **Before publishing**: Run SEO checklist

See `references/seo-guide.md` for full guide.

### Citation & Source Verification

All claims need credible sources:

**Tier 1 (Gold)**: Academic research, Gartner/Forrester, original studies
**Tier 2 (Strong)**: Industry reports, major publications, named experts
**Tier 3 (Contextual)**: Thought leader blogs, podcasts (use carefully)

Always trace statistics to original research. See `references/citations-guide.md`.

### Copyediting & Prose Polish

Final pass to avoid AI slop and ensure human-sounding content:

**Kill list**:
- Hollow intensifiers: "very," "incredibly," "robust," "cutting-edge"
- Weasel phrases: "In today's fast-paced world," "It goes without saying"
- Passive voice that hides the actor
- Throat-clearing before getting to the point

**Instead**: Be specific, be direct, vary rhythm, sound human.

See `references/copyediting-guide.md` for full guide.

---

## Quality Checklist

Before submitting for review:

**Content**
- [ ] Clear audience and goal
- [ ] Strong hook in first 2 sentences
- [ ] Specific examples, data, or customer quotes
- [ ] Claims supported with citations
- [ ] Clear CTA aligned with goal

**Brand**
- [ ] Aligns with Enterpret positioning (`references/brand-voice.md`)
- [ ] Uses canonical terms correctly
- [ ] Avoids deprecated language

**Polish**
- [ ] No AI slop indicators
- [ ] Varied sentence rhythm
- [ ] Active voice where possible
- [ ] Read aloud — sounds human

**SEO** (blogs only)
- [ ] Primary keyword in title, first 100 words, headings
- [ ] Meta description written
- [ ] Internal links included
- [ ] Images have alt text

---

## Reference Files

| File | Use When |
|------|----------|
| `references/templates.md` | Starting any new content piece |
| `references/brand-voice.md` | Checking tone, messaging, positioning |
| `references/writing-samples.md` | Seeing real Enterpret content examples |
| `references/research-guide.md` | Finding industry trends, data, credible sources |
| `references/wisdom-mcp.md` | Finding customer quotes and feedback |
| `references/seo-guide.md` | Optimizing blog content for search |
| `references/citations-guide.md` | Verifying sources and statistics |
| `references/copyediting-guide.md` | Final prose polish, avoiding AI slop |
| `references/review-workflow.md` | Preparing content for peer review |

---

## Quick Start by Task

**"Write an SEO blog post"** (SEO Track)
→ Keyword + SERP analysis → `research-guide.md` → `templates.md` → `seo-guide.md` + `copyediting-guide.md`

**"Write a thought leadership piece"** (Thought Leadership Track)
→ Brief → `research-guide.md` → `wisdom-mcp.md` → Brainstorm 3 spines → Get approval → Draft

**"Create a customer story"** (Thought Leadership Track)
→ `templates.md` (Customer Story) + `wisdom-mcp.md` for quotes

**"Draft a LinkedIn post for Varun"** (Thought Leadership Track)
→ `templates.md` (LinkedIn) + `brand-voice.md` + `writing-samples.md`

**"Research [topic] for content"**
→ `research-guide.md` + web search + `citations-guide.md`

**"Find customer quotes about [topic]"**
→ `wisdom-mcp.md` + Wisdom MCP tools

**"Edit this draft"**
→ `copyediting-guide.md` + `brand-voice.md`

**"Check if this stat is legit"**
→ `citations-guide.md`

**"Optimize for SEO"**
→ `seo-guide.md`
