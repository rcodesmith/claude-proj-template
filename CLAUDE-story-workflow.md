
# Story-Based Development Workflow

Stories are documented in the `/stories/` directory for persistent tracking across sessions.

**Phase 1: Planning**

1. Analyze requirements and research codebase thoroughly
2. Read the given story document under the `stories/` directory
3. Create detailed implementation plan for yourself in the story document under the `stories/` directory
4. Include any updates needed for README.md or CLAUDE.md in tasks
5. Use TodoWrite tool for session state management
6. Define acceptance criteria and implementation details
7. **Do not execute any changes during planning phase**

**Phase 2: Execution**

1. Read plan from the story document and TodoRead tool
2. Execute tasks systematically, checking off completed items in story file
3. Update both story file and TodoWrite tool as progress is made
4. Give high-level explanations of changes at each step
5. Keep changes simple - avoid massive or complex modifications
6. Validate by running appropriate tests (`pytest`, etc.)
7. Add completion summary to story document when finished

# Story File Structure

Create story files in `/stories/` using this template:

**File naming**: `stories/YYYY-MM-DD-brief-description.md`

**Template**:
```markdown
#### Story: [Brief Title]

## Description
What needs to be implemented and why

## Acceptance Criteria  
- [ ] Criterion 1
- [ ] Criterion 2

## Tasks
- [ ] Research existing code patterns
- [ ] Implement core functionality  
- [ ] Add tests
- [ ] Update documentation
- [ ] Validate implementation

## Implementation Notes
- Technical decisions
- Architecture considerations
- Dependencies or blockers

## Validation Steps
How to verify the implementation works

## Completion Summary
[Added by Claude when finished]
```

# Task Management Best Practices

- **Story Files**: Master checklist with checkboxes (- [ ]) for persistent tracking
- **TodoWrite Tool**: Session-specific task management for current work
- **Progress Updates**: Check off tasks in story files as they're completed
- **Cross-Session**: Story files maintain state between Claude sessions

# File Organization

- **Session State**: TodoWrite tool for current session tracking
- **Persistent State**: Story documents under `stories/` for cross-session persistence
- **Task Tracking**: Checkboxes in story files for completion status
