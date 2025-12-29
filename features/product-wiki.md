# Product Wiki

The Product Wiki is your central documentation hub for product specifications, decisions, and knowledge.

## Overview

The Product Wiki serves as:

- **Living documentation** — Always up-to-date product specs
- **Decision log** — Record why choices were made
- **Team alignment** — Single source of truth
- **Onboarding resource** — Help new team members get up to speed

## Structure

The Product Wiki uses the same Notion-style editor as Research Notes, but is specifically designed for product documentation.

### Suggested Organization

```
📚 Product Wiki
├── 🎯 Product Overview
│   ├── Vision & Mission
│   ├── Target Audience
│   └── Value Proposition
├── 🏗️ Architecture
│   ├── System Overview
│   ├── Technical Stack
│   └── Integrations
├── 📋 Specifications
│   ├── Feature Specs
│   ├── API Documentation
│   └── Data Models
├── 📝 Decisions
│   ├── Architecture Decisions
│   ├── Product Decisions
│   └── Design Decisions
└── 📖 Guides
    ├── User Guides
    ├── Admin Guides
    └── Developer Guides
```

## Creating Wiki Pages

### New Page

1. Navigate to **Product** → **Product Wiki**
2. Click **+ New Page** in the sidebar
3. Enter a title
4. Start documenting

### Templates

Use templates for common page types:

#### Feature Specification Template

```markdown
# Feature Name

## Overview
Brief description of the feature

## User Stories
- As a [user], I want to [action] so that [benefit]

## Requirements
### Functional Requirements
- [ ] Requirement 1
- [ ] Requirement 2

### Non-Functional Requirements
- Performance: ...
- Security: ...

## Design
[Link to designs or embed images]

## Technical Notes
Implementation considerations

## Open Questions
- Question 1?
- Question 2?
```

#### Decision Record Template

```markdown
# Decision: [Title]

## Status
Proposed / Accepted / Deprecated / Superseded

## Context
What is the issue we're addressing?

## Decision
What did we decide?

## Consequences
What are the implications?

## Alternatives Considered
What else did we consider?
```

## AI Assistance

### Generate Documentation

Click the **AI Assist** button to:

- Generate initial documentation from feature ideas
- Expand bullet points into full descriptions
- Create user stories from requirements
- Suggest missing sections

### Context-Aware Help

When you ask Molley for help with wiki content, it knows:

- Your product's purpose and audience
- Existing features and their status
- Related research and decisions
- Your company's communication style

### Example Prompts

- "Write a feature specification for [feature name]"
- "Create user stories for this requirement"
- "Suggest what's missing from this documentation"
- "Improve the clarity of this section"

## Linking Content

### Link to Features

Reference features directly:

1. Type `[[` to search
2. Select a feature from Feature Ideas
3. The link shows current status

### Link to Research

Connect documentation to research:

- Link to Research Notes for context
- Reference Knowledge Notebooks
- Include Data Synthesis findings

### Link to Requirements

Show the breakdown:

- Link to specific requirements
- Display requirement status
- Track completion

## Collaboration

### Comments

Add comments to discuss content:

1. Select text
2. Click the comment icon
3. Add your comment
4. Team members are notified

### Version History

Track changes over time:

1. Click **History** in the page menu
2. View previous versions
3. Restore if needed

### Assignments

Assign pages for review:

1. Click **Assign** in the page menu
2. Select team members
3. They receive a notification

## Best Practices

### 1. Keep It Current

Documentation is only useful if it's accurate:

- Update specs when features change
- Archive outdated content
- Review regularly

### 2. Write for Your Audience

Consider who will read this:

- Technical docs for developers
- User guides for customers
- Overview docs for stakeholders

### 3. Use Visuals

Include diagrams and images:

- Architecture diagrams
- User flow charts
- Screenshots
- Wireframes

### 4. Link Liberally

Connect related content:

- Cross-reference between pages
- Link to external resources
- Reference features and requirements

### 5. Document Decisions

Record the "why" not just the "what":

- Why was this approach chosen?
- What alternatives were considered?
- What constraints influenced the decision?

## Next Steps

- [Feature Ideas](/features/feature-ideas) — Capture new ideas
- [Feature Kanban](/features/feature-kanban) — Track feature progress
- [Requirements](/features/requirements) — Break down features
