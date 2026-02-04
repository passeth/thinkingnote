# Thinking Tool

> "A tool that helps you think, not a tool that thinks for you."

## Overview

Thinking Tool is an Obsidian plugin that helps you collect materials from your notes, add your own thoughts, and generate articles with AI assistance. It integrates with Smart Connections to show related notes.

## Philosophy

This plugin embodies "생각의 외주화를 막는 생각 도구" (A tool that prevents outsourcing your thinking):

1. **You** explore and read your notes
2. **You** select meaningful quotes
3. **You** add your own thoughts and reflections
4. **AI** only helps organize at the end

## Features

- **3-Panel Layout**: Source note | Related notes | Material collection
- **Smart Connections Integration**: See semantically related notes
- **Material Collection**: Select text → add your thought → save as callout
- **AI Article Generation**: Get topic suggestions and generate articles
- **Multiple Personas**: Essay, Blog, Academic, Twitter thread styles

## Installation

1. Copy the `thinking-tool` folder to `.obsidian/plugins/`
2. Enable "Thinking Tool" in Settings → Community plugins
3. Configure your AI API key in Settings → Thinking Tool

## Requirements

- Obsidian v1.4.0+
- Smart Connections plugin (for related notes)
- OpenAI or Anthropic API key (for article generation)

## Usage

1. Open any note
2. Click the 🧠 brain icon in the ribbon (or use command palette: "Start Thinking Session")
3. Browse notes and select text you want to collect
4. Right-click → "Add as Material" → add your thought
5. Click related notes in center panel to explore
6. When ready, click "Generate" to create an article

## Material Format

Materials are saved in Obsidian callout format:

```markdown
> [!quote] [[SourceNote]]
> Your selected text here
>
> **My Thought**: Your reflection on this material
```

## Settings

- **AI Provider**: OpenAI or Anthropic (Claude)
- **API Keys**: Your API keys for article generation
- **Material Notes Folder**: Where to save material notes
- **Connections Limit**: How many related notes to show

## Commands

- `Start Thinking Session`: Begin a new session from current note
- `End Thinking Session`: Close the current session
- `Generate Article from Materials`: Open the generation modal

## License

MIT
