# 🌿 Quick Branch Reference Guide

## Creating Branches

```bash
# Create and switch to a new branch
git checkout -b branch-name

# Or using newer Git syntax
git switch -c branch-name
```

## Branch Naming Convention

| Prefix | Purpose | Example |
|--------|---------|---------|
| `feature/` | New features | `feature/add-tests` |
| `fix/` | Bug fixes | `fix/broken-link` |
| `docs/` | Documentation | `docs/update-readme` |
| `style/` | Styling/formatting | `style/css-improvements` |
| `refactor/` | Code refactoring | `refactor/cleanup-code` |

## Common Branch Commands

```bash
# List all branches
git branch -a

# Switch to existing branch
git checkout branch-name
# or
git switch branch-name

# Delete a branch (locally)
git branch -d branch-name

# Delete a branch (forcefully)
git branch -D branch-name

# Rename current branch
git branch -m new-branch-name

# Check current branch
git branch --show-current
```

## Working with Remote Branches

```bash
# Push branch to remote
git push origin branch-name

# Push and set upstream
git push -u origin branch-name

# Fetch all branches from remote
git fetch --all

# List remote branches
git branch -r

# Delete remote branch
git push origin --delete branch-name
```

## Keeping Your Branch Updated

```bash
# Update from main branch
git checkout main
git pull origin main
git checkout your-branch
git merge main

# Or using rebase (cleaner history)
git checkout your-branch
git rebase main
```

## Quick Workflow

```bash
# 1. Get latest code
git pull origin main

# 2. Create feature branch
git checkout -b feature/my-feature

# 3. Make changes and commit
git add .
git commit -m "Add my feature"

# 4. Push to remote
git push origin feature/my-feature

# 5. Create Pull Request on GitHub
```

## Troubleshooting

```bash
# Discard changes in working directory
git restore filename
# or
git checkout -- filename

# Undo last commit (keep changes)
git reset --soft HEAD~1

# Undo last commit (discard changes)
git reset --hard HEAD~1

# Check what changed
git status
git diff

# View commit history
git log --oneline
```

## Best Practices

✅ **DO:**
- Use descriptive branch names
- Create separate branches for each feature/fix
- Keep branches focused and small
- Delete branches after merging
- Pull latest changes before creating branch
- Write clear commit messages

❌ **DON'T:**
- Commit directly to main
- Use generic names like "test" or "temp"
- Keep long-lived feature branches
- Force push to shared branches
- Commit sensitive information

---

For more details, see [CONTRIBUTING.md](CONTRIBUTING.md)
