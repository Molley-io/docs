# Chat Interface

The Molley Chat interface is your primary way to interact with Molley AI.

## Opening Chat

### From the Header

1. Click **Molley Chat** in the top header
2. The chat drawer opens on the right side
3. Start a new conversation or continue existing ones

### Keyboard Shortcut

Press `Alt + M` to toggle the chat drawer.

## Chat Interface Layout

### Thread List

When you first open chat, you see your conversation threads:

- **Recent threads** — Your latest conversations
- **Search** — Find past conversations
- **+ New Chat** — Start a new thread

### Conversation View

Inside a thread:

- **Header** — Thread title, participants, actions
- **Messages** — Conversation history
- **Input** — Type your message
- **Context indicator** — Shows loaded context

## Starting Conversations

### New Thread

1. Click **+ New Chat**
2. Type your message
3. Press Enter or click Send

### Thread Titles

Threads are automatically titled based on the first message. You can:

- Let Molley generate a title
- Edit the title manually

## Sending Messages

### Text Messages

Type in the input field and:

- Press **Enter** to send
- Press **Shift + Enter** for new line

### Adding Context

Add specific content to your message:

1. Click the **+** button in the input
2. Select content type (feature, note, etc.)
3. Choose the specific item
4. It's added as context to your message

## Message Types

### Your Messages

Your messages appear on the right side with:

- Your message content
- Timestamp
- Copy button

### Molley's Responses

AI responses appear on the left with:

- Response content (formatted markdown)
- Timestamp
- Copy button
- Regenerate option

### Context Messages

When context is loaded, you'll see:

- Context type indicator
- Summary of loaded content
- Option to view full context

## Conversation Features

### Copy Messages

Copy any message:

1. Hover over the message
2. Click the copy icon
3. Content is copied to clipboard

### Regenerate Response

Get a different response:

1. Hover over Molley's message
2. Click regenerate
3. A new response is generated

### Delete Messages

Remove messages from the thread:

1. Hover over the message
2. Click delete
3. Confirm deletion

## Managing Threads

### Thread List

View all your conversations:

- Sorted by most recent
- Shows thread title and preview
- Click to open

### Search Threads

Find past conversations:

1. Use the search bar
2. Search by title or content
3. Click result to open

### Delete Threads

Remove a conversation:

1. Open the thread
2. Click the delete icon in the header
3. Confirm deletion

## Participants

### Solo Conversations

By default, threads are between you and Molley.

### Group Conversations

Invite team members to collaborate:

1. Click the participants icon
2. Add team members
3. Everyone can see and contribute

See [Group Conversations](/ai/group-chat) for more details.

## Tips for Effective Chat

### 1. Start with Context

If you need specific help:

- Navigate to the relevant project/feature first
- Context loads automatically
- Or add context manually

### 2. Be Clear and Specific

Good prompts get good responses:

- State what you want clearly
- Provide relevant details
- Specify format if needed

### 3. Iterate

Build on responses:

- Ask follow-up questions
- Request modifications
- Explore alternatives

### 4. Use Threads Wisely

Organize your conversations:

- One topic per thread
- Start new threads for new topics
- Use search to find past discussions

## Example Conversations

### Feature Planning

```
You: I need to add user authentication to our app. 
     What should I consider?

Molley: Based on your project targeting [audience], 
        here are key considerations:
        
        1. Authentication methods...
        2. Security requirements...
        3. User experience...
        
        Would you like me to draft a feature spec?

You: Yes, please include OAuth support.

Molley: Here's a draft specification...
```

### Content Generation

```
You: Write a product description for our landing page.

Molley: Based on your product [name] and target audience 
        of [audience], here's a draft:
        
        [Generated content]
        
        Would you like me to adjust the tone or focus?
```

### Analysis

```
You: What patterns do you see in our recent user feedback?

Molley: Looking at the feedback from the past month, 
        I see these themes:
        
        1. [Theme 1] - mentioned 15 times
        2. [Theme 2] - mentioned 12 times
        ...
        
        The most actionable insight is...
```

## Next Steps

- [Context Awareness](/ai/context) — How context works
- [AI-Powered Features](/ai/features) — AI throughout Molley
- [Group Conversations](/ai/group-chat) — Collaborate with AI
