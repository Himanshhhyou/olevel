# Contributing to LearnAngle

Thank you for your interest in contributing to LearnAngle! This document provides guidelines and instructions for contributing to this project.

## 🌿 Branch Strategy

### Main Branches

- **main**: The primary branch containing stable, production-ready code
- **develop**: Integration branch for features (if used)

### Creating Feature Branches

All development work should be done in dedicated branches. Follow these steps:

#### 1. Update Your Local Repository

```bash
# Fetch the latest changes
git fetch origin

# Make sure you're on main branch
git checkout main

# Pull the latest changes
git pull origin main
```

#### 2. Create a New Branch

Use descriptive branch names following this convention:

```bash
# For new features
git checkout -b feature/short-description

# For bug fixes
git checkout -b fix/issue-description

# For documentation
git checkout -b docs/what-you-are-documenting

# For styling/formatting
git checkout -b style/what-you-are-styling

# For code refactoring
git checkout -b refactor/what-you-are-refactoring
```

**Examples:**
```bash
git checkout -b feature/add-chapter3-tests
git checkout -b fix/broken-navigation-links
git checkout -b docs/add-setup-instructions
git checkout -b style/improve-mobile-responsiveness
git checkout -b refactor/simplify-test-filters
```

#### 3. Make Your Changes

- Write clean, readable code
- Follow the existing code style
- Add comments where necessary
- Test your changes thoroughly

#### 4. Commit Your Changes

Write clear, descriptive commit messages:

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Add Chapter 3 tests for HTML forms"
```

**Commit Message Guidelines:**
- Use present tense ("Add feature" not "Added feature")
- Be specific and descriptive
- Reference issue numbers if applicable (e.g., "Fix #123: Navigation bug")
- Keep first line under 50 characters
- Add detailed description in body if needed

**Good commit messages:**
```
Add search functionality to online tests
Fix mobile menu not closing on link click
Update README with installation instructions
Refactor CSS for better maintainability
```

#### 5. Push Your Branch

```bash
# Push your branch to GitHub
git push origin feature/your-branch-name
```

#### 6. Create a Pull Request

1. Go to the GitHub repository
2. Click "Pull requests" → "New pull request"
3. Select your branch
4. Fill in the PR template with:
   - Clear description of changes
   - Screenshots (if UI changes)
   - Testing steps
   - Related issues

## 📋 What Can You Contribute?

### 1. **New Test Questions**
- Add more chapter-wise tests
- Create practice questions for different topics
- Provide Hindi and English versions

### 2. **Code Examples**
- Add new HTML/CSS examples
- Create mini-projects
- Demonstrate web development concepts

### 3. **Study Materials**
- Add PDF resources
- Create visual guides
- Write tutorials

### 4. **Bug Fixes**
- Fix broken links
- Resolve display issues
- Correct spelling/grammar errors

### 5. **Improvements**
- Enhance UI/UX
- Improve mobile responsiveness
- Optimize performance
- Add accessibility features

### 6. **Documentation**
- Improve README
- Add code comments
- Create setup guides
- Write usage examples

## ✅ Testing Checklist

Before submitting your pull request, ensure:

- [ ] Code works on latest Chrome, Firefox, and Safari
- [ ] All pages display correctly on mobile devices
- [ ] All links work properly
- [ ] No console errors in browser DevTools
- [ ] Code follows existing formatting style
- [ ] Documentation is updated (if applicable)
- [ ] Commit messages are clear and descriptive

## 🎨 Coding Standards

### HTML
- Use semantic HTML5 elements
- Include proper meta tags
- Use descriptive id and class names
- Keep structure clean and organized

### CSS
- Use consistent indentation (2 spaces)
- Group related styles together
- Comment complex sections
- Use meaningful class names
- Prefer flexbox/grid for layouts

### JavaScript
- Use `const` and `let` instead of `var`
- Write clear function names
- Add comments for complex logic
- Handle errors appropriately
- Test edge cases

## 🚫 What NOT to Do

- Don't commit directly to the main branch
- Don't include personal/sensitive information
- Don't add large binary files without reason
- Don't remove functionality without discussion
- Don't ignore code review feedback
- Don't commit `node_modules` or build artifacts

## 📝 Pull Request Process

1. **Create PR** with clear title and description
2. **Wait for review** from maintainers
3. **Address feedback** if requested
4. **Update your PR** based on comments
5. **Merge** will be done by maintainers once approved

## 🤔 Need Help?

- Open an issue for questions
- Check existing issues and PRs
- Review this guide and README.md
- Contact the maintainers

## 📜 Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Maintain a positive environment

## 🎯 Quick Reference

```bash
# Get latest code
git pull origin main

# Create branch
git checkout -b feature/my-feature

# Check status
git status

# Stage changes
git add .

# Commit changes
git commit -m "Description"

# Push branch
git push origin feature/my-feature

# Update branch with latest main
git checkout main
git pull origin main
git checkout feature/my-feature
git merge main
```

---

**Thank you for contributing to LearnAngle! 🎓✨**
