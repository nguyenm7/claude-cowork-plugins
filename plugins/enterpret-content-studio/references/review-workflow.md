# Content Review Workflow

Peer review process for Enterpret marketing content using Notion.

---

## Overview

All content goes through peer review before publishing. This ensures quality, brand consistency, and diverse perspectives.

**Workflow stages**:
1. Draft → 2. Review Request → 3. Feedback → 4. Revision → 5. Approval → 6. Publish

---

## Notion Setup

### Content Database Structure

Create a Notion database for content with these properties:

| Property | Type | Options |
|----------|------|---------|
| Title | Title | — |
| Status | Select | Draft, In Review, Revision, Approved, Published |
| Content Type | Select | Blog, Case Study, LinkedIn (Company), LinkedIn (Executive), Social, Other |
| Author | Person | — |
| Reviewer | Person | — |
| Target Publish Date | Date | — |
| Channel | Multi-select | Website, LinkedIn, Newsletter, Twitter/X |
| Priority | Select | High, Medium, Low |
| Brief Link | URL | Link to content brief (if separate) |

### Draft Page Template

Each content draft should include:

```
# [Content Title]

## Metadata
- **Type**: [Blog / Case Study / LinkedIn / etc.]
- **Author**: [Name]
- **Target date**: [Date]
- **Primary channel**: [Where it will publish]

## Brief
[Link to brief or summarize: audience, goal, key message]

---

## Draft Content

[Full draft here]

---

## Review Notes

### Reviewer: [Name]
**Date reviewed**:
**Overall**: [Ready / Needs revision / Major rework]

**Feedback**:
-
-
-

---

## Revision Log
| Date | Author | Changes made |
|------|--------|--------------|
| | | |
```

---

## Reviewer Assignments

### By Content Type

| Content Type | Primary Reviewer | Secondary (Optional) |
|--------------|------------------|---------------------|
| Blog posts (thought leadership) | Varun or Kevin | Michael |
| Blog posts (product) | Birkan | Arnav |
| Case studies | Jack | Michael |
| LinkedIn (Company) | Kevin | Michael |
| LinkedIn (Varun) | Kevin or Michael | — |
| LinkedIn (other exec) | Kevin | — |
| Social media | Kevin | — |
| Product announcements | Birkan | Varun |

### Reviewer Responsibilities

**Primary reviewer**:
- Review within 2 business days
- Check for brand voice alignment
- Verify factual accuracy
- Assess structure and flow
- Provide actionable feedback

**Secondary reviewer** (if assigned):
- Spot-check after primary review
- Focus on specific expertise (product accuracy, customer accuracy, etc.)

---

## Feedback Guidelines

### For Reviewers

**What to check**:
- [ ] Does the hook grab attention?
- [ ] Is the main message clear?
- [ ] Does it follow brand voice guidelines?
- [ ] Are claims supported with evidence/quotes?
- [ ] Is the CTA appropriate?
- [ ] Is it the right length for the channel?
- [ ] Are there any factual errors?

**How to give feedback**:
- Use Notion comments for specific line edits
- Use the Review Notes section for overall feedback
- Be specific: "The opening feels generic" → "Consider starting with a customer pain point or surprising stat"
- Prioritize: Note which changes are essential vs. nice-to-have

### For Authors

**Preparing for review**:
- Ensure draft is complete (not a rough outline)
- Include all sources/references
- Note any specific questions for reviewers
- Tag reviewer in Notion and send Slack message

**Responding to feedback**:
- Address all comments before resubmitting
- Use the Revision Log to document changes
- If disagreeing with feedback, discuss directly rather than ignoring

---

## Turnaround Expectations

| Stage | Timeframe |
|-------|-----------|
| Draft to Review Request | Author sets based on publish date |
| Review feedback | 2 business days |
| Author revision | 1-2 business days |
| Final approval | 1 business day |

**For urgent content** (same-day or next-day publish):
- Slack the reviewer directly
- Mark as "High" priority in Notion
- Expect abbreviated review (focus on accuracy and brand voice only)

---

## Approval Process

### Standard Approval
1. Reviewer marks status as "Approved" in Notion
2. Reviewer adds approval comment: "Approved for publish" with any final notes
3. Author publishes and updates status to "Published"

### Conditional Approval
- "Approved with minor edits" = Author can make changes and publish without re-review
- "Approved pending [specific item]" = Author must address item; can self-approve after

### Escalation
If author and reviewer disagree on feedback:
1. Discuss directly (Slack or quick call)
2. If unresolved, escalate to Kevin (marketing decisions) or Varun (strategic positioning)

---

## Publishing Checklist

Before hitting publish:

- [ ] Final proofread complete
- [ ] All links tested
- [ ] Images/graphics finalized and uploaded
- [ ] SEO metadata filled in (blogs)
- [ ] CTA links correct
- [ ] Scheduled for optimal time (if applicable)
- [ ] Cross-posting plan ready (LinkedIn, newsletter, etc.)

After publishing:

- [ ] Update Notion status to "Published"
- [ ] Add published URL to Notion
- [ ] Share in #marketing Slack channel
- [ ] Queue social promotion if planned

---

## Slack Integration

### Notifications

Use Slack for:
- Review requests: "@[reviewer] - ready for review: [Notion link]"
- Feedback complete: "@[author] - feedback added: [Notion link]"
- Approvals: Quick confirmation in thread

### Channel
- Use #content-reviews (or create if doesn't exist)
- Keep threads organized by content piece

---

## Quick Reference

**To request a review**:
1. Finalize draft in Notion
2. Set status to "In Review"
3. Assign reviewer
4. Slack reviewer with link

**To complete a review**:
1. Add feedback in Notion (comments + Review Notes)
2. Set status to "Revision" or "Approved"
3. Slack author

**To publish**:
1. Get approval in Notion
2. Complete publishing checklist
3. Publish
4. Update Notion status
5. Share in Slack
