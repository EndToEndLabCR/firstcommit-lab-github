# First Commit Lab — GitHub

A hands-on lab to practice Git and GitHub by making your first contribution.

## 📖 Start Here

**New to Git or GitHub?** → Read the [Git & GitHub Guide](https://endtoendlabcr.github.io/endtoendlabcr-docs/docs/guides-and-tutorials/git-github-guide) first. It covers everything you need to know before making your first commit.

**Already comfortable with Git?** → Jump to [Lab Instructions](#-lab-instructions) below.

## 🎯 What You'll Learn

- How Git tracks changes (commits, branches)
- How GitHub enables collaboration (forks, PRs)
- The complete workflow: fork → branch → commit → push → PR → merge
- How to write good commit messages
- How to review and respond to PR feedback

## 🧪 Lab Instructions

Your task: Create a markdown file with your name and GitHub username.

### 1. Fork This Repo

Click **Fork** at the top-right of this page to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/firstcommit-lab-github.git
cd firstcommit-lab-github
```

### 3. Add Upstream Remote

```bash
git remote add upstream https://github.com/EndToEndLabCR/firstcommit-lab-github.git
git remote -v   # verify you see origin (yours) and upstream (original)
```

### 4. Create a Branch

```bash
git checkout -b feature/your-username
```

### 5. Create Your File

Copy an existing file as a template:

```bash
cp 2025/alonsovn.md 2025/yourusername.md
```

Edit it with your information:

```markdown
# Your Full Name

**GitHub:** [@yourusername](https://github.com/yourusername)
**Role:** Your role or what you do
**Year:** 2025

## About

A short sentence about you.
```

### 6. Commit and Push

```bash
git add 2025/yourusername.md
git commit -m "docs: add yourusername profile"
git push -u origin feature/your-username
```

### 7. Open a Pull Request

1. Go to the **original repo**: https://github.com/EndToEndLabCR/firstcommit-lab-github
2. You should see a prompt: _"your-username had recent pushes — Compare & pull request"_
3. Click it, add a description, and create the PR
4. Or go directly to: `https://github.com/EndToEndLabCR/firstcommit-lab-github/compare/main...YOUR-USERNAME:feature/your-username?expand=1`

### 8. Wait for Review

A team member will review your PR. If there are comments, address them and push again. Once approved, your PR will be merged! 🎉

## 📚 Resources

- [Git & GitHub Guide](https://endtoendlabcr.github.io/endtoendlabcr-docs/docs/guides-and-tutorials/git-github-guide) — Theory and commands (hosted on our docs site)
- [Conventional Commits](https://www.conventionalcommits.org/) — Commit message standard
- [GitHub Docs](https://docs.github.com/en/get-started) — Official GitHub documentation
- [Git Handbook](https://guides.github.com/introduction/git-handbook/) — Official Git guide

## 👥 Participants

| Username | File | PR |
|---|---|---|
| Alonsovn | [alonsovn.md](./2025/alonsovn.md) | — |
| FranciscoCCR | [Francisco.md](./2025/Francisco.md) | [#7](https://github.com/EndToEndLabCR/firstcommit-lab-github/pull/7) |
| DerianCampos | [deriancampos.md](./2025/deriancampos.md) | [#6](https://github.com/EndToEndLabCR/firstcommit-lab-github/pull/6) |
| genesis-morales | [genesismc.md](./2025/genesismc.md) | [#8](https://github.com/EndToEndLabCR/firstcommit-lab-github/pull/8) |
| TommyVana | [tommyvn.md](./2025/tommyvn.md) | [#4](https://github.com/EndToEndLabCR/firstcommit-lab-github/pull/4) |
| YosserQuesada | [yosserquesada.md](./2025/yosserquesada.md) | [#12](https://github.com/EndToEndLabCR/firstcommit-lab-github/pull/12) |

_Add your name above when your PR is merged!_
