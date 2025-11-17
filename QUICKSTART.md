# Quick Start Guide for Team Members

This guide will help you quickly get started with editing and contributing to the Arivu-Kalaam project.

## 🚀 Quick Setup (5 minutes)

### 1. Fork & Clone
```bash
# Fork the repository on GitHub, then:
git clone https://github.com/YOUR-USERNAME/Arivu-Kalaam.git
cd Arivu-Kalaam
git remote add upstream https://github.com/gokul12072006/Arivu-Kalaam.git
```

### 2. Create Your Branch
```bash
# For new features:
git checkout -b feature/your-feature-name

# For bug fixes:
git checkout -b fix/bug-description
```

### 3. Make Changes
Edit any files you need to change using your favorite editor.

### 4. Commit & Push
```bash
git add .
git commit -m "Brief description of your changes"
git push origin your-branch-name
```

### 5. Create Pull Request
1. Go to your fork on GitHub
2. Click "New Pull Request"
3. Fill out the template
4. Submit!

## 🎯 Common Tasks

### Updating Your Branch
```bash
git fetch upstream
git rebase upstream/main
```

### Fixing Mistakes
```bash
# Undo last commit (keeps changes):
git reset --soft HEAD~1

# Discard all local changes:
git checkout .
```

### Checking Status
```bash
git status                    # See what's changed
git diff                      # See detailed changes
git log --oneline -5         # See recent commits
```

## 📋 Collaboration Checklist

Before submitting your pull request:

- [ ] Code is tested and working
- [ ] Commit messages are clear
- [ ] Branch is up to date with main
- [ ] No unnecessary files added
- [ ] Pull request template is filled out

## 💡 Tips

1. **Small Changes**: Make small, focused changes rather than large sweeping modifications
2. **Descriptive Commits**: Write clear commit messages that explain *why* not just *what*
3. **Regular Updates**: Keep your branch updated with upstream changes
4. **Ask Questions**: Don't hesitate to ask if you're unsure about something

## 🔗 Resources

- [Full Contributing Guide](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [GitHub Issues](https://github.com/gokul12072006/Arivu-Kalaam/issues)

## 🆘 Need Help?

- Read the [CONTRIBUTING.md](CONTRIBUTING.md) for detailed instructions
- Check existing [issues](https://github.com/gokul12072006/Arivu-Kalaam/issues) for answers
- Open a new issue if you need assistance
- Reach out to project maintainers

---

**Remember**: Everyone was a beginner once. Don't be afraid to experiment and learn!
