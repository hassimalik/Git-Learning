# 📌 Git Learning Roadmap

## Stage 0: Basics – Understanding Git
**Goal:** Know what Git is and how it works conceptually.

- What is Git vs GitHub/GitLab/Bitbucket
- Version control concepts: repo, commit, branch, merge, remote
- Local vs remote repos

**Practice:**
- Install Git on your machine
- Run `git init`, `git add`, `git commit` on a small folder
- Check status with `git status` and history with `git log`

---

## Stage 1: Local Git Mastery
**Goal:** Be confident working with Git on your computer

- `git add`, `git commit`
- `git status`, `git diff`
- `git log` with different flags (`--oneline`, `--graph`)
- Undoing changes: `git checkout`, `git reset`, `git revert`
- Stashing: `git stash`, `git stash apply`
- Ignoring files: `.gitignore`

**Practice:**
- Make multiple commits in a test repo
- Modify a file, stash it, and apply the stash later
- Try undoing a commit

---

## Stage 2: Branching & Merging
**Goal:** Understand parallel development

- Creating branches: `git branch`, `git checkout -b`
- Switching branches: `git checkout`
- Merging branches: `git merge`
- Conflict resolution (the most common corporate challenge!)

**Practice:**
- Create a feature branch, modify code, merge into `main`
- Intentionally create a conflict and resolve it

---

## Stage 3: Working with Remotes
**Goal:** Collaborate using GitHub/Bitbucket/Azure DevOps

- `git remote add origin ...`
- `git push` / `git pull` / `git fetch`
- Tracking branches
- Cloning repos: `git clone`

**Practice:**
- Push your local repo to GitHub
- Clone a repo and make changes
- Pull changes from others

---

## Stage 4: Professional Workflows
**Goal:** Learn corporate-style Git usage

- Branching strategies:
  - Git Flow: `main`, `develop`, `feature`, `release`, `hotfix`
  - GitHub Flow: lightweight `main` + feature branches
- Pull Requests / Merge Requests
- Code review process
- Rebase vs merge: `git rebase`
- Tagging releases: `git tag v1.0.0`

**Practice:**
- Simulate a small team workflow with 2-3 branches
- Practice PR workflow locally using forks
- Tag a release version

---

## Stage 5: Advanced Git
**Goal:** Be confident in complex scenarios

- Interactive rebase: `git rebase -i`
- Cherry-pick commits: `git cherry-pick <hash>`
- Resetting history safely: `git reset --soft/hard`
- Bisecting to find bugs: `git bisect`
- Working with Git LFS for large files
- Submodules for multi-repo projects

**Practice:**
- Rewrite commit history with interactive rebase
- Use `git bisect` to find a bug
- Add a submodule and update it

---

## Stage 6: Git in Corporate Environment & CI/CD
**Goal:** Work exactly like a pro in a team and automate deployments

- Use `.gitignore` properly for configs and secrets
- Professional commit messages: `type: description`
- Avoid pushing sensitive data
- Understanding code ownership and approvals
- **Automated CI/CD pipelines**:
  - CI: Run tests and builds automatically on push or pull request
  - CD: Automatically deploy code to staging or production after passing CI
  - Tools: GitHub Actions, Azure Pipelines, GitLab CI
- Git triggers pipelines: pushing branches or merging PRs starts CI/CD

**Practice:**
- Work on a collaborative project with multiple branches
- Follow commit conventions
- Create a simple GitHub Action workflow to **run tests on push**  
- Merge a branch and see CI/CD trigger automatically

---

## Stage 7: Visualization & Debugging
**Goal:** Understand your repo and debug efficiently

- Visualize history: `git log --graph --oneline --all`
- Use GUI tools: GitKraken, SourceTree, GitHub Desktop
- Git aliasing for efficiency: `git config --global alias.co checkout`
- Debugging with Git: find which commit introduced a bug using `git bisect`  
