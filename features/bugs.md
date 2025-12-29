# Bug Tracking

Track, prioritize, and resolve issues in your product with Molley's bug tracking system.

## Overview

Bug tracking in Molley helps you:

- **Capture issues** from any source
- **Prioritize effectively** based on severity
- **Track resolution** through to completion
- **Learn from patterns** to prevent future bugs

## Creating Bugs

### Quick Add

1. Navigate to **Product** → **Bugs**
2. Click **+ New Bug**
3. Enter a title and description
4. Submit

### Detailed Bug Report

For complete bug reports:

| Field | Description |
|-------|-------------|
| **Title** | Clear, specific summary |
| **Description** | Detailed explanation |
| **Steps to Reproduce** | How to trigger the bug |
| **Expected Behavior** | What should happen |
| **Actual Behavior** | What actually happens |
| **Severity** | Critical, High, Medium, Low |
| **Environment** | Browser, OS, version |
| **Screenshots** | Visual evidence |

### From Feedback

Bugs can come from feedback forms:

1. Review feedback submissions
2. Click **Create Bug** on relevant feedback
3. Bug is created with linked context

## Bug Severity

### Severity Levels

| Severity | Description | Response Time |
|----------|-------------|---------------|
| **Critical** | System down, data loss, security issue | Immediate |
| **High** | Major feature broken, no workaround | Same day |
| **Medium** | Feature impaired, workaround exists | This week |
| **Low** | Minor issue, cosmetic | When time allows |

### Setting Severity

Consider:

- **Impact** — How many users affected?
- **Frequency** — How often does it occur?
- **Workaround** — Can users work around it?
- **Data** — Is data at risk?

## Bug Status

### Workflow

```
🆕 New → 🔍 Triaged → 🔧 In Progress → ✅ Resolved → 🔒 Closed
                                            ↓
                                        🔄 Reopened
```

### Status Definitions

| Status | Description |
|--------|-------------|
| **New** | Just reported, not reviewed |
| **Triaged** | Reviewed, prioritized |
| **In Progress** | Being fixed |
| **Resolved** | Fix complete, needs verification |
| **Closed** | Verified fixed |
| **Reopened** | Issue returned |

## Bug Details

Click any bug to view full details:

### Information Tab

- Title and description
- Severity and status
- Reporter and assignee
- Created and updated dates

### Reproduction Tab

- Steps to reproduce
- Expected vs actual behavior
- Environment details
- Screenshots and attachments

### Activity Tab

- Status changes
- Comments and discussion
- Related commits or changes

### Related Tab

- Linked features
- Related requirements
- Similar bugs

## Organization

### Filtering

Find bugs quickly:

- **Status** — Show specific statuses
- **Severity** — Filter by severity
- **Assignee** — Show assigned bugs
- **Date range** — Recent bugs

### Sorting

Order bugs by:

- Severity (critical first)
- Created date
- Last updated
- Status

### Search

Search by:

- Title keywords
- Description content
- Reporter name

## Bug Archive

Resolved bugs move to the archive:

1. Navigate to **Bugs** → **Archive**
2. View historical bugs
3. Search for patterns
4. Reference past solutions

## AI Assistance

### Bug Analysis

Ask Molley about bugs:

- "What's causing this bug?"
- "Suggest a fix for this issue"
- "Are there similar bugs in our history?"

### Pattern Detection

AI can identify patterns:

- Recurring issues
- Common root causes
- Areas needing attention

### Context Awareness

When analyzing bugs, Molley knows:

- Your product's architecture
- Related features and requirements
- Historical bug patterns
- Recent changes

## Collaboration

### Assignments

Assign bugs to team members:

1. Open the bug
2. Click **Assign**
3. Select team member
4. They receive notification

### Comments

Discuss bugs:

- Ask clarifying questions
- Share investigation findings
- Propose solutions
- Update on progress

### Mentions

@mention team members:

- Notify specific people
- Request input
- Escalate issues

## Best Practices

### 1. Write Clear Titles

Good titles help triage:

- ✅ "Login fails with special characters in password"
- ❌ "Login broken"

### 2. Include Reproduction Steps

Make bugs reproducible:

```markdown
## Steps to Reproduce
1. Go to login page
2. Enter email: test@example.com
3. Enter password: p@ss!word
4. Click "Sign In"

## Expected
User is logged in

## Actual
Error: "Invalid credentials"
```

### 3. Add Context

Include helpful information:

- Browser and version
- Operating system
- Account type
- Recent actions

### 4. Attach Evidence

Screenshots and recordings help:

- Capture the error state
- Show the steps
- Include console errors

### 5. Triage Regularly

Keep the bug list healthy:

- Review new bugs daily
- Set appropriate severity
- Assign to team members
- Close resolved bugs

### 6. Learn from Bugs

Prevent future issues:

- Identify root causes
- Update documentation
- Add tests
- Improve processes

## Integration

### With Features

Link bugs to features:

- Track bugs per feature
- Identify problematic areas
- Prioritize fixes

### With Requirements

Connect to requirements:

- Bugs may indicate incomplete requirements
- Update requirements when fixing bugs

### With Feedback

Close the loop:

- Link bugs to user feedback
- Notify users when fixed
- Improve satisfaction

## Next Steps

- [Feature Kanban](/features/feature-kanban) — Track feature progress
- [Feedback Forms](/features/feedback-forms) — Collect user reports
- [Requirements](/features/requirements) — Improve specifications
