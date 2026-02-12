# Gitton

**Git Client for Vibe Coding**

[Download](https://jsers.dev/service/gitton)

Gitton is a Git client designed for the AI coding era. Run Claude Code, Cursor CLI, and other AI assistants directly in the integrated terminal. Features AI-powered commit message generation, code review, and PR description generation. Extensible with JavaScript plugins.

![Gitton Working Copy](https://jsers.dev/images/gitton-working-copy.png)

## Plugins

Extend Gitton with JavaScript. Add sidebar panels, settings tabs, context menus, and more. Use any framework you like—React, Vue, Svelte.

```bash
npx create-gitton-plugin
```

[Creating Gitton Plugins](https://jsers.dev/service/gitton/blog/creating-gitton-plugins)

## Philosophy

Gitton represents a paradigm shift in development tools for the AI era. With AI coding assistants like Claude Code, Cursor CLI, and Aider, developers spend less time in traditional editors and more time in terminals.

**Terminal-First Approach** - Rather than another code editor, Gitton integrates a terminal for AI instruction. Give instructions to AI in the terminal, review results and commit in a powerful Git client.

**Advanced Git Features** - AI-assisted development requires *more* sophisticated Git capabilities. Since AI generates large code blocks that may include unintended changes, you need granular version control.

**GitHub-Exclusive Focus** - Deep GitHub integration enables PR management, inline commenting, AI-generated PR descriptions, and automated code reviews—all within the app.

**Strip unnecessary features while thoroughly refining essential ones.** For the AI era, that means: powerful Git operations, terminal integration, and seamless GitHub workflows—without editor complexity.

## Features

### Visual History & Navigation

![Gitton History](https://jsers.dev/images/gitton-history.png)

- **Intuitive Graph View** - Visualize your project history with color-coded branch graphs
- **Easy Operations** - Cherry-pick, revert, and reset commits with a click
- **Reflog Support** - Complete operation history for easy recovery from mistakes

### Branches & Reflog

![Gitton Branches](https://jsers.dev/images/gitton-branches.png)

### GitHub Integration

![Gitton Pull Requests](https://jsers.dev/images/gitton-pull-requests.png)

- **Pull Requests** - Create, review, and merge PRs without leaving the app
- **AI-Generated PR Descriptions** - Let AI write your PR descriptions from commit diffs
- **AI Code Review** - Get intelligent feedback on your changes

![Gitton AI Review](https://jsers.dev/images/gitton-ai-review.png)

### AI-Powered Workflows

- **Multi-Provider Support** - OpenAI, Anthropic, Google, and Ollama
- **Conventional Commit Messages** - Auto-generate meaningful commit messages
- **Security Analysis** - AI-powered security scanning of your changes

### Parallel Development with Worktrees

![Gitton Worktrees](https://jsers.dev/images/gitton-worktrees.png)

- **Multiple Worktrees** - Work on different branches simultaneously
- **Independent Sessions** - Run separate AI tool sessions in each worktree

### Integrated Terminal

![Gitton Terminal](https://jsers.dev/images/gitton-terminal.png)

- **AI Tool Ready** - Claude Code, Cursor, GitHub Copilot - use any tool you like
- **Full Shell Access** - Execute any command within your repository

### Plugin System

Extend Gitton's functionality with plugins:
- Add custom sidebar panels
- Add settings tabs
- Add context menu items
- Register Git hooks (pre-commit, post-push, etc.)

## Plugin Development

Extend Gitton with plugins. Add sidebar panels, settings tabs, context menus, and Git hooks.

See [gitton-plugins](https://github.com/gitton-dev/gitton-plugins) for examples and documentation.

## Pricing

- **Free Trial** - 7 days
- **Pro** - $19.99 one-time purchase (no subscription)

## Links

- [Website](https://jsers.dev/service/gitton)
- [Philosophy](https://jsers.dev/service/gitton/blog/gitton-philosophy)

## License

MIT License

## Author

godai
