# Claude Code Guide

## What is Claude Code?

Claude Code is Anthropic's official CLI tool that provides an interactive coding assistant powered by Claude AI. It helps with software engineering tasks including debugging, feature development, code refactoring, and more.

## Key Features

- **Interactive Development**: Real-time assistance with coding tasks
- **File Operations**: Read, write, and edit files across your codebase
- **Command Execution**: Run bash commands, git operations, and more
- **Code Search**: Search through your codebase using glob patterns and grep
- **Task Management**: Track complex multi-step tasks with built-in todo lists
- **Web Integration**: Fetch documentation and search the web for answers

## Common Commands

### Getting Help
```bash
/help
```

### Clearing the Session
```bash
/clear
```

### Custom Slash Commands
You can create custom slash commands in `.claude/commands/` directory.

## Working with Git

Claude Code can help you with:
- Creating commits with descriptive messages
- Creating pull requests
- Reviewing code changes
- Managing branches

Example:
```
"Create a commit with my staged changes"
"Create a pull request for this feature"
```

## Best Practices

1. **Be Specific**: Provide clear, detailed instructions for what you want to accomplish
2. **Provide Context**: Share relevant file paths, error messages, or code snippets
3. **Iterative Development**: Break complex tasks into smaller steps
4. **Review Changes**: Always review code changes before committing

## Current Project Configuration

- **Project Name**: ng-claude-test
- **Working Directory**: `/Users/lc.cucchiaro/Documents/Sviluppo/Angular/my-angular-app`
- **Git Repository**: https://github.com/devLuca15/ng-claude-test.git
- **Git User**: DevLuca15
- **Git Email**: devluca15@gmail.com
- **Platform**: macOS
- **Angular Version**: 20.1.0

## Useful Resources

- Documentation: https://docs.claude.com/en/docs/claude-code
- Feedback/Issues: https://github.com/anthropics/claude-code/issues

## Examples

### Creating a New Feature
```
"Help me create a new Angular component for user authentication"
```

### Debugging
```
"I'm getting a TypeScript error in app.component.ts, can you help fix it?"
```

### Code Review
```
"Review my recent changes and suggest improvements"
```

### Refactoring
```
"Refactor the UserService to use async/await instead of promises"
```

## Tips

- Claude Code can work with multiple files simultaneously
- Use natural language to describe what you want to accomplish
- You can ask for explanations of existing code
- Claude Code respects your coding style and conventions
