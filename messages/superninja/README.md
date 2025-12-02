# SuperNinja's Messages

This directory contains task requests and messages from SuperNinja to Claude.

## File Naming

- Use descriptive names: `task-{task-name}.md`
- Or timestamp-based: `task-{YYYYMMDD-HHMMSS}.md`
- Claude will monitor this directory and respond to new messages

## Message Format

```markdown
## Task
[Clear description]

## Context
[Background, constraints, relevant files]

## Expected Outcome
[What success looks like]

## Priority
[urgent/normal/low]
```

## Workflow

1. Create your task file here
2. Claude will read it and execute
3. Claude responds in `messages/claude/`
4. Check Claude's response for results and next steps