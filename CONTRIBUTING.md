# Contributing to Forking-Around

First off, thank you for considering contributing to **Forking-Around**! Whether you are squashing a bug, writing docs, optimizing performance, or proposing a brand-new project, your efforts are welcome here.

We keep our workflow lightweight so you can spend less time filling out bureaucracy and more time building software.

---

## 🚀 Contribution Workflow

```
 1. Find/Propose     2. Discuss          3. Fork & Branch    4. Implement & Test    5. Open PR
  [Issue / Idea] ──> [Approach] ──────> [git checkout -b] ─> [Write code & tests] ─> [Submit PR]
```

### 1. Find an Issue or Idea
Browse existing issues across our repositories or open a new one. 
- Want to report a bug? Use the [Bug Report Template](.github/ISSUE_TEMPLATE/bug.yml).
- Have a feature or new repository idea? Use the [Idea Template](.github/ISSUE_TEMPLATE/idea.yml).

> **Pitching New Projects:** We actively encourage members and contributors to propose entirely new project ideas! If you have a developer tool, AI experiment, protocol prototype, or library you want to build under Forking-Around, submit an Idea issue to start the discussion.

### 2. Discuss the Approach
For non-trivial changes or new project proposals, leave a comment on the issue discussing your planned technical implementation before writing code. This ensures alignment and avoids redundant effort.

### 3. Fork & Branch
Fork the repository to your GitHub account and clone it locally. Create a descriptive branch name off `main`:

```bash
git checkout -b feat/add-agent-memory-store
# or
git checkout -b fix/cli-parser-edgecase
```

### 4. Implement the Change
Write clean, readable code. Keep commits focused and atomic with clear, descriptive commit messages.

### 5. Add or Update Tests and Documentation
- Ensure existing tests pass.
- Write unit or integration tests for new functionality.
- Update relevant `README.md` files or inline code comments.

### 6. Verify Locally
Run build scripts, linters, and test suites prior to pushing.

### 7. Open a Pull Request
Push your branch to your fork and submit a Pull Request against the `main` branch. 
- Fill out the PR template completely.
- Reference the related issue (e.g., `Closes #42`).
- Be responsive to code reviews — feedback is aimed at shipping robust software together.

---

## 🛠️ Code & Commit Guidelines

- **Commit Messages:** Use concise, imperative commit messages (e.g., `feat: add async stream handler`, `fix: prevent memory leak in buffer cleanup`).
- **Code Style:** Follow the linting and formatting rules established in the respective repository (e.g., `eslint`, `black`, `clippy`, `gofmt`).
- **No Scope Creep:** Keep pull requests focused on a single logical change or feature.

---

## 🤝 Community & Expectations

- Be respectful and constructive in reviews and issue discussions.
- We adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

Thank you for building open source with us!
