# Wisdom MCP Server Guide

Use the Wisdom MCP server to search, analyze, and retrieve real customer feedback for content creation.

---

## What Wisdom Provides

The Wisdom MCP server connects to Enterpret's Customer Knowledge Graph, giving you access to:

- **Real customer quotes** — Verbatim feedback from support tickets, surveys, reviews, calls
- **Feedback themes** — Categorized insights across products, features, sentiments
- **Customer context** — Account data, segments, revenue impact, usage patterns
- **Trend analysis** — What's changing over time, anomalies, emerging issues

---

## When to Use Wisdom

### Content Brainstorming
- "What are customers saying about [feature/problem]?"
- "What pain points come up most for [persona/segment]?"
- "What outcomes are customers achieving?"

### Finding Quotes for Content
- "Find customer quotes about [topic] from enterprise accounts"
- "Get verbatim feedback about [specific pain point]"
- "Find success stories related to [use case]"

### Validating Content Claims
- "Is [claim] supported by customer feedback?"
- "How many customers mention [problem]?"
- "What's the sentiment around [feature]?"

### Case Study Research
- "Pull all feedback from [customer account]"
- "What use cases does [customer] mention?"
- "What results has [customer] reported?"

---

## Available Tools

### search_knowledge_graph
Natural language search across all customer feedback.

**Use for**: Open-ended exploration, finding relevant feedback on a topic

**Example queries**:
- "customers struggling with manual tagging"
- "positive feedback about time savings"
- "enterprise accounts mentioning ROI"

### execute_cypher_query
Structured queries against the Knowledge Graph for precise data retrieval.

**Use for**: Specific data needs, filtering by customer attributes, aggregations

**Example use cases**:
- Find quotes from customers in a specific industry
- Get feedback volume by theme over time
- Find customers with specific outcomes (e.g., "reduced support tickets")

### get_schema
Understand the Knowledge Graph structure before writing queries.

**Use for**: Learning what entities and relationships are available

---

## Content Creation Workflows

### Blog Post: Finding Supporting Quotes

1. **Identify the claim** you want to support
   - Example: "Teams waste hours on manual feedback tagging"

2. **Search for relevant feedback**
   ```
   search_knowledge_graph: "manual tagging time consuming frustrating"
   ```

3. **Filter for quotable results**
   - Look for specific, vivid language
   - Prefer quotes that name concrete pain (hours, tools, frustration)
   - Check customer context (title, company size) for credibility

4. **Format for content**
   - Get permission if using customer name
   - Use anonymized quotes if no permission: "A Head of Support at a Fortune 500 company shared..."

### Case Study: Deep Customer Research

1. **Pull all feedback from the customer account**
   ```
   search_knowledge_graph: "[Customer Name] feedback"
   ```

2. **Identify key themes**
   - What problems did they mention before Enterpret?
   - What outcomes have they reported?
   - What features do they mention most?

3. **Find quotable moments**
   - Look for "before/after" language
   - Find specific metrics or time savings
   - Identify emotional language (frustrated → relieved)

4. **Validate with the customer**
   - Share draft quotes for approval
   - Ask if metrics can be shared publicly

### Thought Leadership: Validating Industry Trends

1. **Hypothesize the trend**
   - Example: "Companies are drowning in feedback but starving for insights"

2. **Search for supporting patterns**
   ```
   search_knowledge_graph: "too much feedback overwhelmed can't keep up"
   ```

3. **Quantify if possible**
   - "X% of feedback mentions this theme"
   - "This issue appears across Y customer segments"

4. **Find contrasting voices**
   - Search for customers who solved the problem
   - Use for the "solution" section of your content

---

## Quote Quality Checklist

Before using a customer quote in content:

- [ ] **Specific**: Names a concrete problem, tool, or outcome
- [ ] **Vivid**: Uses emotional or memorable language
- [ ] **Credible**: Speaker has relevant title/context
- [ ] **Permissioned**: Customer approved for public use (or anonymize)
- [ ] **Recent**: Feedback is within last 12 months (unless historical context)
- [ ] **Representative**: Reflects a pattern, not an outlier opinion

### Good Quote Example
> "Before Enterpret, I spent every Monday morning tagging 200 tickets by hand. Now I start the week with insights instead of spreadsheets."
> — Head of Support, Series B SaaS

### Weak Quote Example
> "Enterpret is good."
> — Unknown

---

## Privacy & Attribution Rules

### When to Use Full Attribution
- Customer has given explicit permission
- Quote is from a public case study or testimonial
- Customer is in the "approved for marketing" list

### When to Anonymize
- No explicit permission obtained
- Feedback contains sensitive business info
- Quote is from support ticket or internal survey

### Anonymization Patterns
- "A VP of Product at a leading fintech..."
- "One customer shared..."
- "Feedback from enterprise accounts shows..."

### Never Use
- Quotes with identifying details that weren't approved
- Feedback that mentions competitors negatively
- Internal-only customer communications

---

## Integration with Content Workflow

### Step 2: Research & Gather Inputs
Use Wisdom to:
- Find 3-5 potential quotes for your piece
- Validate claims with real feedback data
- Discover angles you hadn't considered

### Step 3: Draft Content
Embed quotes naturally:
- Use quotes to support claims, not replace them
- Introduce quotes with context
- Let the customer voice reinforce your point

### Step 4: Review
Verify:
- All quotes are properly attributed or anonymized
- Customer names are on the approved list
- Quotes are used in appropriate context
