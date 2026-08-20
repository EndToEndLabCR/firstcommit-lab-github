# First Commit Lab — GitHub

A hands-on lab to practice Git and GitHub by making your first contribution.

## What You'll Learn

- How Git tracks changes — commits, branches, and history
- How GitHub enables collaboration — forks, pull requests, and code review
- The full contribution workflow: **fork → branch → commit → push → PR → merge**
- How to write clear, conventional commit messages
- How to respond to review feedback

---

## Lab Instructions

Your task: Create a markdown profile file with your name and GitHub username.

### 1. Fork This Repo

Click **Fork** at the top-right of this page to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/firstcommit-lab-github.git
cd firstcommit-lab-github
```

### 3. Add the Upstream Remote

```bash
git remote add upstream https://github.com/EndToEndLabCR/firstcommit-lab-github.git
git remote -v   # verify: origin (your fork) + upstream (original)
```

### 4. Create a Feature Branch

```bash
git checkout -b feature/your-username
```

### 5. Create Your Profile File

Copy the template and rename it to your username:

```bash
cp PARTICIPANT-TEMPLATE.md participants/yourusername.md
```

Then edit the new file with your information:

```markdown
# Your Full Name

**GitHub:** [@yourusername](https://github.com/yourusername)
**Role:** Your role or what you do
**Year:** 2025

## About

A short sentence about you.
```

### 6. Commit & Push

```bash
git add participants/yourusername.md
git commit -m "docs: add yourusername profile"
git push -u origin feature/your-username
```

### 7. Open a Pull Request

1. Go to the **original repo**: <https://github.com/EndToEndLabCR/firstcommit-lab-github>
2. GitHub should show a _"Compare & pull request"_ banner — click it
3. Add a short description and submit
4. **Or use this URL** (replace `YOUR-USERNAME`):
   `https://github.com/EndToEndLabCR/firstcommit-lab-github/compare/main...YOUR-USERNAME:feature/your-username?expand=1`

### 8. Wait for Review

A team member will review your PR. If feedback is left, address it and push again. Once approved, your PR will be merged!

---
