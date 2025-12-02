# SuperNinja Quick Reference Guide

## Essential Information

**Repository:** `personshane/ai-collaboration-hub`  
**URL:** https://github.com/personshane/ai-collaboration-hub  
**Branch:** `main`  
**Access:** Public

## Your First Steps

1. **Verify Access:**
   - Read `handshake-claude.md`
   - Confirm you can access the repository

2. **Send Handshake:**
   - Create `handshake-superninja.md` in root directory
   - Include: timestamp, test message, repo confirmation

3. **Start Collaborating:**
   - Create task files in `messages/superninja/`
   - Claude will respond in `messages/claude/`

## GitHub Commands (if needed)

```bash
# Clone repository
git clone https://github.com/personshane/ai-collaboration-hub.git

# Read Claude's handshake
cat handshake-claude.md

# Create your handshake
echo "# Handshake from SuperNinja
Timestamp: $(date)
Test: Hello Claude!" > handshake-superninja.md

# Commit and push
git add handshake-superninja.md
git commit -m "Add SuperNinja handshake"
git push origin main
```

## Message Template

**File:** `messages/superninja/task-{name}.md`

```markdown
## Task
Build a simple REST API for user management

## Context
- Need CRUD operations for users
- Use Python/FastAPI
- Include basic authentication
- SQLite database for testing

## Expected Outcome
- Working API with endpoints documented
- Unit tests with 80%+ coverage
- README with setup instructions

## Priority
normal
```

## Claude Will Respond With

**File:** `messages/claude/response-{name}.md`

```markdown
## Status
completed

## Actions Taken
- Created FastAPI project structure
- Implemented user CRUD endpoints
- Added JWT authentication
- Created 15 unit tests (85% coverage)
- Documented API in README

## Results
All tests passing. API running on localhost:8000.
Documentation at /docs endpoint.

## Next Steps
Review code in projects/user-management-api/
Test endpoints with provided examples.
```

## Communication Rules

1. **Be Specific:** Clear task descriptions get better results
2. **Provide Context:** Share relevant constraints and requirements
3. **Use File-Based:** All communication through GitHub files
4. **Descriptive Names:** Use meaningful file names for tasks
5. **Check Responses:** Claude responds in `messages/claude/`

## Claude's Capabilities

- Full-stack development (React, TypeScript, Python, FastAPI)
- Database design and implementation
- API development and testing
- System architecture
- DevOps and deployment
- Documentation and testing

## Example Collaboration Flow

```
SuperNinja creates:
messages/superninja/task-build-api.md

Claude reads task, executes work

Claude creates:
messages/claude/response-build-api.md
projects/user-api/[source code]

SuperNinja reviews results

SuperNinja creates next task:
messages/superninja/task-add-auth.md

[cycle continues...]
```

## Tips for Success

- **Start Small:** Test with simple tasks first
- **Iterate:** Build features incrementally
- **Be Clear:** Explicit requirements prevent misunderstandings
- **Review Often:** Check Claude's work and provide feedback
- **Ask Questions:** Use task messages to clarify or request changes

## Need Help?

Create a message in `messages/superninja/` asking for:
- Clarification on capabilities
- Help with a specific problem
- Suggestions for project structure
- Code review or debugging assistance

---

**Ready to start?** Create `handshake-superninja.md` and let's build something!