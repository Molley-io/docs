# Feature Kanban

The Feature Kanban provides a visual workflow for managing features from ideation to release.

## Overview

The Kanban board shows your features organized by status:

```
┌─────────────┬─────────────┬─────────────┬─────────────┬─────────────┐
│   Backlog   │ Consideration│  Refinement │ In Progress │  Released   │
├─────────────┼─────────────┼─────────────┼─────────────┼─────────────┤
│  Feature A  │  Feature D  │  Feature G  │  Feature J  │  Feature M  │
│  Feature B  │  Feature E  │  Feature H  │  Feature K  │  Feature N  │
│  Feature C  │  Feature F  │  Feature I  │  Feature L  │             │
└─────────────┴─────────────┴─────────────┴─────────────┴─────────────┘
```

## Kanban Columns

### Backlog

New ideas that haven't been evaluated yet.

- Ideas enter here by default
- Review regularly to move forward or archive
- No limit on items

### In Consideration

Ideas being actively evaluated.

- Discuss with team
- Assess value and effort
- Decide: refine or archive

### In Refinement

Approved ideas being detailed.

- Add requirements
- Write specifications
- Estimate effort
- Prepare for development

### In Progress

Features currently being built.

- Active development
- Track progress through requirements
- Limit work in progress (WIP)

### Released

Shipped features.

- Celebrate completion
- Gather feedback
- Plan iterations

## Using the Kanban

### Drag and Drop

Move features between columns:

1. Click and hold a feature card
2. Drag to the target column
3. Release to update status

### Card Details

Each card shows:

- **Title** — Feature name
- **Priority** — Color-coded indicator
- **Requirements** — Progress count (e.g., "3/5")
- **Category** — Grouping tag

Click a card to open full details.

### Quick Actions

Hover over a card for quick actions:

- **Edit** — Open detail view
- **Archive** — Move to archive
- **Delete** — Remove permanently

## Detailed View

Access the Detailed View for a requirements-focused Kanban:

1. Click **Detailed View** in the sidebar
2. Or expand from the Feature Kanban

### Requirements Kanban

The Detailed View shows requirements within features:

```
┌─────────────────────────────────────────────────────────────────────┐
│ Feature: User Authentication                                        │
├─────────────┬─────────────┬─────────────┬─────────────┬─────────────┤
│   To Do     │ In Progress │    Done     │             │             │
├─────────────┼─────────────┼─────────────┼─────────────┼─────────────┤
│  Login form │  OAuth      │  Password   │             │             │
│  Signup     │             │  reset      │             │             │
└─────────────┴─────────────┴─────────────┴─────────────┴─────────────┘
```

### Swim Lanes

Features appear as horizontal swim lanes:

- Each feature is a row
- Requirements flow through columns
- Visual progress at a glance

## Filtering and Sorting

### Filter Options

- **Category** — Show specific categories
- **Priority** — Filter by priority level
- **Assignee** — Show assigned items

### Search

Find specific features:

1. Use the search bar
2. Search by title or description
3. Results highlight matching cards

## Work in Progress (WIP) Limits

### Why Limit WIP?

Too many items in progress leads to:

- Context switching
- Delayed completion
- Quality issues

### Setting Limits

Consider limiting:

- **In Progress** — 3-5 items per person
- **In Refinement** — 5-10 items total

## Collaboration

### Assignments

Assign features to team members:

1. Open the feature
2. Click **Assign**
3. Select team member(s)

### Comments

Discuss on the board:

1. Open a feature card
2. Add comments
3. @mention for notifications

### Activity Feed

Track changes:

- Status changes
- Assignments
- Comments
- Updates

## AI Assistance

### Board Analysis

Ask Molley about your board:

- "What should we prioritize next?"
- "Are we taking on too much?"
- "What's blocking progress?"

### Feature Help

Get help with specific features:

- "Help me break down this feature"
- "What requirements am I missing?"
- "Suggest acceptance criteria"

## Best Practices

### 1. Limit Work in Progress

Focus on finishing, not starting:

- Complete items before starting new ones
- Identify and remove blockers
- Celebrate completions

### 2. Regular Standups

Review the board daily or weekly:

- What moved?
- What's blocked?
- What's next?

### 3. Keep Cards Updated

Accurate status helps everyone:

- Move cards promptly
- Update requirements progress
- Add notes for context

### 4. Use Categories

Group related features:

- Easier to see themes
- Better prioritization
- Clearer roadmap

### 5. Archive Completed Work

Keep the board clean:

- Move released features to archive
- Review archive periodically
- Learn from past work

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Search | `Ctrl/Cmd + F` |
| New feature | `N` |
| Refresh | `R` |

## Next Steps

- [Requirements](/features/requirements) — Break down features
- [Bug Tracking](/features/bugs) — Track issues
- [Feature Ideas](/features/feature-ideas) — Add more ideas
