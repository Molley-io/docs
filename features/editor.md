# Rich Text Editor

The Molley editor is a powerful Notion-style block editor used across Research Notes and Product Wiki. It provides rich text editing with AI assistance.

## Overview

The editor supports:

- **Rich text formatting** — Bold, italic, underline, strikethrough, inline code
- **Block types** — Headings, paragraphs, quotes, code blocks, callouts
- **Lists** — Bullet lists, numbered lists, checklists (to-do)
- **Tables** — Full table support with headers
- **AI assistance** — Context-aware writing help via `/ai` command
- **Voice input** — Dictate content using speech recognition

## Text Formatting

### Inline Styles

| Style | Toolbar | Shortcut |
|-------|---------|----------|
| **Bold** | Bold button | `Ctrl/Cmd + B` |
| *Italic* | Italic button | `Ctrl/Cmd + I` |
| <u>Underline</u> | Underline button | `Ctrl/Cmd + U` |
| ~~Strikethrough~~ | Strikethrough button | — |
| `Inline code` | Code button | `Ctrl/Cmd + E` |

### Links

Insert links via the **Insert** menu:

1. Click **Insert** → **Link**
2. Enter the URL
3. Optionally enter display text
4. Click **Insert**

## Block Types

Use the block type dropdown or type shortcuts:

| Block | Dropdown | Description |
|-------|----------|-------------|
| Normal | Paragraph | Regular text |
| Heading 1 | H1 | Large section header |
| Heading 2 | H2 | Medium section header |
| Heading 3 | H3 | Small section header |
| Heading 4 | H4 | Smallest header |
| Code Block | Code | Monospace code formatting |
| Quote | Quote | Block quote with left border |

## Lists

### Bullet List

Click the bullet list button or start a line with `- ` or `* `:

- First item
- Second item
  - Nested item

### Numbered List

Click the numbered list button or start a line with `1. `:

1. First step
2. Second step
3. Third step

### Checklist (To-Do)

Click the checklist button to create interactive checkboxes:

- [ ] Unchecked item
- [x] Checked item (click to toggle)

Checklists are perfect for:
- Task tracking
- Meeting action items
- Requirements checklists

## Callouts

Callouts are highlighted boxes for important information. Insert via **Insert** menu:

| Type | Use Case |
|------|----------|
| **Info** | General information, tips |
| **Warning** | Cautions, important notes |
| **Success** | Confirmations, completed items |
| **Danger** | Errors, critical warnings |

## Tables

### Creating Tables

1. Click **Insert** → **Table**
2. Set the number of rows and columns
3. Optionally include a header row
4. Click **Insert**

### Table Navigation

- **Tab** — Move to next cell
- **Shift + Tab** — Move to previous cell
- **Arrow keys** — Navigate between cells

## Horizontal Rule

Insert a horizontal divider via **Insert** → **Horizontal Rule** to separate content sections.

---

## Text Alignment

Use the alignment dropdown to align text:

- **Left** — Default alignment
- **Center** — Centered text
- **Right** — Right-aligned text
- **Justify** — Justified text

## Indentation

Use the indent buttons to:

- **Increase Indent** — Indent content right
- **Decrease Indent** — Outdent content left

Works with paragraphs and list items for nested structures.

## AI Assistance

### Using the AI Assistant

Trigger AI help in two ways:

1. **Slash command** — Type `/ai` followed by space
2. **Toolbar** — Click **/ Commands** → **/ai**

### How It Works

1. The AI popup appears at your cursor
2. Type your request (e.g., "Write an introduction", "Expand this idea")
3. Press **Ctrl+Enter** or click **Generate**
4. Review the generated content
5. Click **Insert** to add it or **Discard** to cancel

### Context-Aware

The AI assistant knows:

- Your document content before and after the cursor
- Your company and project context
- The type of content you're writing

### Example Prompts

- "Write a summary of the above"
- "Expand this into a full paragraph"
- "Create bullet points for this topic"
- "Improve the clarity of this section"
- "Generate user stories for this feature"

## Voice Input

### Using Voice to Text

1. Click the **microphone** button in the toolbar
2. Speak clearly into your microphone
3. Your speech is transcribed and inserted at the cursor
4. Click the microphone again to stop

Voice input requires browser microphone permissions.

## Fullscreen Mode

Click the fullscreen button (top-right of toolbar) to expand the editor to full screen. Click again or press **Escape** to exit.

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Bold | `Ctrl/Cmd + B` |
| Italic | `Ctrl/Cmd + I` |
| Underline | `Ctrl/Cmd + U` |
| Inline Code | `Ctrl/Cmd + E` |
| Link | `Ctrl/Cmd + K` |
| Undo | `Ctrl/Cmd + Z` |
| Redo | `Ctrl/Cmd + Shift + Z` |
| AI Assistant | Type `/ai` + Space |

## Auto-Save

Content is automatically saved after 3 seconds of inactivity. The save button shows:

- **Save** — Unsaved changes
- **Saved** (green) — Recently saved

You can also manually save at any time by clicking the **Save** button.

## Tips

### Use Headings for Structure

Organize long documents with headings:

```
# Main Topic (H1)
## Subtopic (H2)
### Detail (H3)
```

### Callouts for Emphasis

Use callouts to highlight:

- **Info** — Tips and additional context
- **Warning** — Things to watch out for
- **Success** — Completed milestones
- **Danger** — Critical issues

### Checklists for Tasks

Track progress with checklists:

- [ ] Draft content
- [ ] Review with team
- [ ] Publish

### AI for First Drafts

Use AI to generate initial content, then refine:

1. Type `/ai` and describe what you need
2. Insert the generated content
3. Edit and personalize
