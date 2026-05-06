# AGENTS.md

Static HTML/CSS CV site. No build step, no dependencies, no test framework.

- `opencode.json` sets all permissions to "ask" - expect confirmation prompts
- Edit HTML/CSS directly; no compilation or codegen
- Styles in `styles.css`, content in `index.html`

## Git
- Commit only when explicitly requested by the user
- Commit messages: concise, present tense, describe the exact change 
- Never force push to main; warn user if requested
- Push to remote only when explicitly asked

- Commit Types:
Type 	Purpose
feat 	New feature
fix 	Bug fix
docs 	Documentation only
style 	Formatting/style (no logic)
refactor 	Code refactor (no feature/fix)
perf 	Performance improvement
test 	Add/update tests
build 	Build system/dependencies
ci 	CI/config changes
chore 	Maintenance/misc
revert 	Revert commit
- Generate Commit Message
    Type: What kind of change is this?
    Scope: What area/module is affected?
    Description: One-line summary of what changed (present tense, imperative mood, <72 chars)

- Execute Commit

# Single line
git commit -m "<type>[scope]: <description>"

