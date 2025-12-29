# Context Awareness

Molley AI's power comes from understanding your business context. This page explains how context works and how to use it effectively.

## How Context Works

### Automatic Context

Molley automatically loads context based on where you are in the app:

```
Company Level
└── Company profile, mission, values, target market

    Project Level
    └── + Product details, target audience, value proposition

        Feature Level
        └── + Feature description, requirements, status

            Specific Item
            └── + Item details, related content
```

### Context Hierarchy

Context builds hierarchically:

1. **Company context** — Always available
2. **Project context** — Added when in a project
3. **Feature context** — Added when viewing a feature
4. **Item context** — Added when viewing specific items

### What's Included

#### Company Context

- Company name and description
- Mission and vision
- Target market
- Industry and positioning
- Team culture and values

#### Project Context

- Product name and description
- Target audience details
- Value proposition
- Key features summary
- Project goals

#### Feature Context

- Feature title and description
- Current status
- Requirements list
- Related research
- Comments and discussions

## Using Context Effectively

### Let Context Load

When you need help with something specific:

1. Navigate to that item first
2. Open Molley Chat
3. Context loads automatically
4. Ask your question

### Example: Feature Help

**Without navigation:**
```
You: Help me write requirements for user authentication.

Molley: Here are general requirements for authentication...
        [Generic response]
```

**With navigation:**
```
[Navigate to your "User Authentication" feature first]

You: Help me write requirements for this feature.

Molley: Based on your product [name] targeting [audience], 
        and considering your existing features, here are 
        specific requirements for User Authentication:
        
        [Contextual, specific response]
```

### Adding Manual Context

Sometimes you need to add specific context:

1. Find the item you want to reference
2. Click the **Molley** button on that item
3. Select **Add to Chat**
4. The item is added as context

### Context Indicators

The chat shows what context is loaded:

- **Company** badge — Company info loaded
- **Project** badge — Project info loaded
- **Feature** badge — Feature info loaded
- **+N items** — Additional context added

## Context in Different Areas

### Research

When working with research:

- Research notes content is available
- Related documents are referenced
- Synthesis findings are included

**Example prompts:**
- "Summarize my research on competitors"
- "What patterns do you see in these notes?"
- "Help me synthesize these findings"

### Product Development

When working with features:

- Feature descriptions are loaded
- Requirements are included
- Related features are referenced

**Example prompts:**
- "What requirements am I missing?"
- "How does this feature relate to others?"
- "Help me prioritize these requirements"

### Growth & Marketing

When working with outreach:

- Product positioning is loaded
- Target audience is included
- Existing campaigns are referenced

**Example prompts:**
- "Write an email for this audience"
- "Suggest messaging angles"
- "How should we position against competitors?"

### Feedback

When working with feedback:

- Form responses are available
- User context is included
- Historical feedback is referenced

**Example prompts:**
- "What are users saying about this feature?"
- "Identify themes in recent feedback"
- "What should we prioritize based on feedback?"

## Prompt Templates

Molley uses prompt templates to structure AI interactions. These templates:

- Include relevant context automatically
- Ensure consistent, high-quality responses
- Are optimized for specific use cases

### How Templates Work

When you use AI features (like "Improve with AI"), Molley:

1. Selects the appropriate template
2. Fills in your context (company, project, feature)
3. Adds your specific request
4. Sends to the AI

### Template Benefits

- **Consistency** — Similar requests get similar quality
- **Context** — Always includes relevant information
- **Efficiency** — No need to explain your business each time

## Best Practices

### 1. Navigate First

Before asking for help:

- Go to the relevant project
- Open the specific feature or item
- Let context load

### 2. Be Specific

Even with context, specificity helps:

- "Help me with this feature" → Good
- "Write 3 user stories for this feature focusing on mobile users" → Better

### 3. Add Relevant Context

If the automatic context isn't enough:

- Add specific research notes
- Include competitor information
- Reference related features

### 4. Check Context Indicators

Before asking:

- Verify the right context is loaded
- Add missing context if needed
- Remove irrelevant context

### 5. Iterate with Context

Build on previous responses:

- Follow-up questions use the same context
- Add new context as needed
- Reference previous responses

## Troubleshooting

### Context Not Loading

If context seems missing:

1. Refresh the page
2. Navigate away and back
3. Check that the item has content

### Wrong Context

If responses seem off-topic:

1. Check context indicators
2. Navigate to the correct item
3. Start a new thread if needed

### Too Much Context

If responses are too broad:

1. Be more specific in your request
2. Focus on one item at a time
3. Remove unnecessary context

## Next Steps

- [AI-Powered Features](/ai/features) — AI throughout Molley
- [Group Conversations](/ai/group-chat) — Collaborate with AI
- [Chat Interface](/ai/chat) — Using the chat
