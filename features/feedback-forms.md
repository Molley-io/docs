# Feedback Forms

Create and embed feedback forms to collect user insights directly from your website or app.

## Overview

Feedback Forms help you:

- **Collect user feedback** in real-time
- **Measure satisfaction** with NPS and CSAT
- **Gather insights** with custom questions
- **Track submissions** and analyze trends

## Form Types

### NPS (Net Promoter Score)

Measure customer loyalty:

- "How likely are you to recommend us?" (0-10)
- Automatic NPS calculation
- Follow-up question for context

### CSAT (Customer Satisfaction)

Measure satisfaction with specific interactions:

- "How satisfied are you?" (1-5 stars or emoji)
- Quick and easy for users
- Great for post-interaction feedback

### Comment

Open-ended feedback:

- Free-text response
- No rating required
- Best for qualitative insights

### Custom

Build your own form:

- Multiple question types
- Conditional logic
- Flexible structure

## Creating Forms

### New Form

1. Navigate to **Product** → **Feedback Forms**
2. Click **+ Create Form**
3. Select form type
4. Configure settings

### Form Settings

| Setting | Description |
|---------|-------------|
| **Name** | Internal name for the form |
| **Title** | Displayed to users |
| **Description** | Optional context for users |
| **Type** | NPS, CSAT, Comment, or Custom |
| **Status** | Active, Draft, Paused, Archived |

### NPS Configuration

For NPS forms:

- **Question text** — Customize the main question
- **Follow-up** — Ask why they gave that score
- **Thank you message** — Shown after submission

### CSAT Configuration

For CSAT forms:

- **Question text** — What are you measuring?
- **Scale type** — Stars, emoji, or numbers
- **Follow-up** — Optional additional question

### Custom Forms

Build custom forms with:

- **Text questions** — Short or long answer
- **Rating questions** — Scale of your choice
- **Multiple choice** — Select one or many
- **Conditional logic** — Show questions based on answers

## Embedding Forms

### Getting the Code

1. Open your form
2. Click **Get Code** or view the SDK Help
3. Copy the embed snippet

### JavaScript SDK

```html
<script src="https://sdk.molley.io/feedback.js"></script>
<script>
  MolleyFeedback.init({
    publicKey: 'your-public-key',
    formId: 'your-form-id',
    user: {
      id: 'user-123',
      email: 'user@example.com',
      name: 'John Doe'
    }
  });
</script>
```

### Trigger Options

Control when forms appear:

- **On page load** — Show immediately
- **After delay** — Wait X seconds
- **On exit intent** — When user moves to leave
- **On click** — Triggered by button click
- **Programmatic** — Call from your code

### Targeting

Show forms to specific users:

- By user segment
- By page URL
- By user action
- By percentage (sampling)

## Managing Submissions

### Viewing Submissions

1. Open a form
2. Click **Submissions**
3. View all responses

### Submission Details

Each submission shows:

- **Response** — The actual feedback
- **User** — Who submitted (if identified)
- **Date** — When submitted
- **Page** — Where they were
- **Metadata** — Additional context

### Filtering

Filter submissions by:

- Date range
- Score (for NPS/CSAT)
- User segment
- Keywords

### Export

Export submissions for analysis:

- CSV format
- Select date range
- Include all fields

## Analytics

### NPS Dashboard

For NPS forms:

- **NPS Score** — Overall score (-100 to 100)
- **Distribution** — Promoters, Passives, Detractors
- **Trend** — Score over time
- **Comments** — Qualitative feedback

### CSAT Dashboard

For CSAT forms:

- **Average score** — Mean satisfaction
- **Distribution** — By rating level
- **Trend** — Score over time

### Response Rates

Track engagement:

- Views vs submissions
- Completion rate
- Drop-off points

## AI Assistance

### Analyze Feedback

Ask Molley about your feedback:

- "What are the main themes in our feedback?"
- "Why are detractors unhappy?"
- "What do promoters love about us?"

### Generate Insights

Get actionable insights:

- "Summarize this week's feedback"
- "What should we prioritize based on feedback?"
- "Identify trends in our NPS comments"

### Context Awareness

When analyzing feedback, Molley knows:

- Your product and features
- Recent changes and releases
- Historical feedback patterns

## Form Status

### Status Options

| Status | Description |
|--------|-------------|
| **Draft** | Not yet published |
| **Active** | Collecting responses |
| **Paused** | Temporarily stopped |
| **Archived** | No longer in use |

### Managing Status

- **Activate** — Start collecting
- **Pause** — Stop temporarily (keep data)
- **Archive** — Stop permanently

## Best Practices

### 1. Keep It Short

Respect user time:

- NPS: 2 questions max
- CSAT: 1-2 questions
- Custom: 5 questions max

### 2. Ask at the Right Time

Timing matters:

- After key actions
- Not too frequently
- When context is fresh

### 3. Close the Loop

Act on feedback:

- Respond to negative feedback
- Thank promoters
- Show you're listening

### 4. Segment Analysis

Different users, different insights:

- Analyze by user type
- Compare segments
- Identify patterns

### 5. Track Trends

One response isn't a trend:

- Look at patterns over time
- Compare periods
- Identify changes

## Integration

### With Bug Tracking

Turn feedback into bugs:

- Create bug from feedback
- Link for context
- Track resolution

### With Feature Ideas

Feedback informs features:

- Create ideas from feedback
- Prioritize based on demand
- Close the loop when shipped

### With CRM

Connect to customers:

- Link feedback to companies
- Understand customer sentiment
- Prioritize by customer value

## Next Steps

- [Bug Tracking](/features/bugs) — Track issues from feedback
- [Feature Ideas](/features/feature-ideas) — Turn feedback into features
- [CRM](/features/crm) — Connect to customers
