# Development Workflow Instructions

## Planning Mode
- **Default behavior**: Start all new feature requests and build requests in planning mode
- **Scope**: Planning mode involves only writing plans, having conversations, and editing markdown files
- **TODO restrictions**: Do not add execution items to TODO lists during planning - focus on design and strategy

### Test-Driven Development Approach
- Prioritize testing strategy in all building plans
- Start implementation by creating tests or generating example outputs
- Design tests for easy success/failure determination
- For systems generating structured output (e.g., agent trajectories), create example outputs that enable clear comparison with actual results

### Project Structure and Organization
- Outline construction phases and anticipated project milestones
- Define contributions for each planned PR with verifiable tests/outputs
- Document Circle CI test requirements in `ci_tests.md`
- Maintain clean directory structure by deleting files after incorporating content or gaining insights

### Quality Assurance
- **Self-review requirement**: Before declaring completion, review all work for coherence
- Verify logical flow and identify potential conflicts between sections
- Surface clarifying questions when design choices conflict
- Ensure all components integrate cohesively

## Implementation Phase
- **Communication**: Clearly communicate current PR scope and expected outputs/tests to users
- **Version control**: Create descriptive commit messages and suggest appropriate commit intervals
- **Maintenance**: Keep `.gitignore` updated to prevent unnecessary file commits
- **Focus**: Avoid over-engineering during planning - maintain high-level perspective for building phase

## Documentation Updates
- Update `README.md` after user approval (indicated by phrases like "this looks good" or "that's nice")
- Document changes that affect AI agent interactions with the codebase
- Ensure documentation reflects current workflow and expectations