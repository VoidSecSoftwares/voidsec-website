# Contributing to VoidSecSoftwares Website

Thank you for your interest in contributing! This document provides guidelines and information for contributors.

## 🎯 How to Contribute

### Reporting Bugs

1. Check if the bug has already been reported in [Issues](https://github.com/VoidSecSoftwares/voidsec-website/issues)
2. If not, create a new issue with:
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser/device information
   - Screenshots if applicable

### Suggesting Features

1. Check existing issues for similar suggestions
2. Create a new issue with the `enhancement` label
3. Describe the feature and its use case

### Submitting Changes

1. **Fork** the repository
2. **Create** a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make** your changes
4. **Test** thoroughly
5. **Commit** with a clear message:
   ```bash
   git commit -m "feat: add new feature description"
   ```
6. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open** a Pull Request

## 📝 Commit Convention

We use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — New feature
- `fix:` — Bug fix
- `docs:` — Documentation changes
- `style:` — Code style changes (formatting, no logic change)
- `refactor:` — Code refactoring
- `perf:` — Performance improvements
- `test:` — Adding tests
- `chore:` — Maintenance tasks

Examples:
```
feat: add dark mode toggle
fix: resolve mobile navigation bug
docs: update README with setup instructions
style: format CSS with consistent indentation
```

## 🎨 Code Style

### HTML
- Use semantic HTML5 elements
- Include `alt` text for all images
- Use `aria-label` for accessibility
- Indent with 2 spaces

### CSS
- Use CSS custom properties (variables)
- Follow BEM naming convention
- Keep animations performant (use `transform` and `opacity`)
- Mobile-first responsive design
- Indent with 2 spaces

### JavaScript
- Use vanilla JavaScript (no frameworks)
- Follow ES6+ syntax when possible
- Add comments for complex logic
- Handle errors gracefully
- Indent with 2 spaces

## ♿ Accessibility

- Respect `prefers-reduced-motion`
- Ensure keyboard navigation works
- Maintain proper color contrast
- Use semantic HTML structure
- Add ARIA labels where needed

## 🧪 Testing

Before submitting a PR, verify:

- [ ] Site works in Chrome, Firefox, Safari, Edge
- [ ] Responsive on mobile, tablet, desktop
- [ ] All animations work correctly
- [ ] GitHub API data loads properly
- [ ] No console errors
- [ ] Accessibility features work

## 📋 Pull Request Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] Other (describe)

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Tested on Edge
- [ ] Tested on mobile

## Checklist
- [ ] Code follows project style
- [ ] Comments added for complex code
- [ ] Documentation updated
- [ ] No new warnings
```

## ❓ Questions?

Feel free to open an issue for any questions about contributing!

Thank you for contributing! 🚀