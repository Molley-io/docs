# Requirements

Requirements break down features into specific, actionable items that can be tracked and completed.

## Overview

Requirements help you:

- **Decompose features** into manageable pieces
- **Track progress** at a granular level
- **Estimate effort** more accurately
- **Assign work** to team members
- **Ensure completeness** before release

## Creating Requirements

### From a Feature

1. Open a feature in Feature Ideas
2. Go to the **Requirements** tab
3. Click **+ Add Requirement**
4. Enter the requirement details

### Requirement Fields

| Field | Description |
|-------|-------------|
| **Title** | Clear, specific name |
| **Description** | Detailed explanation |
| **Status** | To Do, In Progress, Done |
| **Priority** | Low, Medium, High, Critical |
| **Estimate** | Effort estimate (optional) |
| **Assignee** | Team member responsible |

### Writing Good Requirements

#### Be Specific

- ✅ "Add email validation with error message on blur"
- ❌ "Validate form"

#### Be Testable

- ✅ "Password must be at least 8 characters with one number"
- ❌ "Strong password required"

#### Be Independent

- ✅ "User can reset password via email link"
- ❌ "Password stuff" (too vague, too broad)

## Requirement Groups

Organize requirements into logical groups:

### Creating Groups

1. Click **+ Create Group**
2. Enter a group name
3. Drag requirements into the group

### Example Groups

For a "User Authentication" feature:

- **Login** — Login form, remember me, error handling
- **Registration** — Signup form, email verification
- **Password** — Reset flow, strength requirements
- **OAuth** — Google, GitHub, social logins

## Requirements Kanban

View requirements in Kanban format:

### Columns

| Column | Description |
|--------|-------------|
| **To Do** | Not started |
| **In Progress** | Currently working |
| **Done** | Completed |

### Using the Board

1. Navigate to **Detailed View** in the sidebar
2. See all features with their requirements
3. Drag requirements between columns
4. Track progress visually

### Swim Lanes

Each feature appears as a swim lane:

- Feature name as the row header
- Requirements flow through columns
- Progress visible at a glance

## AI Assistance

### Generate Requirements

Click **AI Assist** to:

- Generate requirements from feature description
- Suggest missing requirements
- Break down complex requirements

### Example Prompts

- "Break down this feature into requirements"
- "What requirements am I missing?"
- "Suggest acceptance criteria for this requirement"
- "Estimate effort for these requirements"

### Context Awareness

When generating requirements, Molley considers:

- The feature's purpose and scope
- Your product's technical context
- Similar features in your product
- Industry best practices

## Tracking Progress

### Feature Progress

Each feature shows requirement progress:

- **Count** — "5/8 requirements done"
- **Percentage** — Visual progress bar
- **Status** — Overall feature status

### Burndown

Track completion over time:

- Requirements completed per day/week
- Remaining work estimate
- Projected completion

## Collaboration

### Assignments

Assign requirements to team members:

1. Open the requirement
2. Click **Assign**
3. Select team member

### Comments

Discuss specific requirements:

- Ask clarifying questions
- Share implementation notes
- Report blockers

### Notifications

Team members are notified when:

- Assigned to a requirement
- Mentioned in comments
- Requirement status changes

## Best Practices

### 1. Right-Size Requirements

Not too big, not too small:

- **Too big** — "Build user management" (should be multiple requirements)
- **Too small** — "Add semicolon to line 42" (too granular)
- **Just right** — "Add email validation with error messages"

### 2. Include Acceptance Criteria

Define "done" clearly:

```markdown
## Requirement: Password Reset Email

### Acceptance Criteria
- [ ] User receives email within 1 minute
- [ ] Email contains reset link
- [ ] Link expires after 24 hours
- [ ] Link can only be used once
- [ ] User sees confirmation message
```

### 3. Estimate Consistently

Use a consistent scale:

- **T-shirt sizes** — S, M, L, XL
- **Story points** — 1, 2, 3, 5, 8, 13
- **Hours** — 1h, 2h, 4h, 8h, 16h

### 4. Update Status Promptly

Keep the board accurate:

- Move to "In Progress" when starting
- Move to "Done" when complete
- Add notes for context

### 5. Review Before Release

Before marking a feature as released:

- All requirements should be "Done"
- Review acceptance criteria
- Test the complete feature

## Integration with Other Features

### Product Wiki

Link requirements to documentation:

- Reference specifications
- Link to design documents
- Connect to technical docs

### Bug Tracking

When bugs are found:

- Link bugs to requirements
- Track regressions
- Update requirements if needed

### Feedback Forms

Connect user feedback:

- Link feedback to requirements
- Prioritize based on user input
- Close the loop when shipped

## Next Steps

- [Feature Kanban](/features/feature-kanban) — Visual workflow
- [Bug Tracking](/features/bugs) — Track issues
- [Product Wiki](/features/product-wiki) — Document specifications
