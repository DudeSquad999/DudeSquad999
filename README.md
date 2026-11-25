<div align="center">
  <img src="assets/profile-header.svg" alt="Hi, I'm Aidan. I build tools for research, writing, and code." width="100%">

  <p>
    <strong>Local-first AI · Research & writing workspaces · Developer tooling</strong>
  </p>

  <p>
    Software that helps you think clearly, work locally, and stay in control.
  </p>

  <p>
    <a href="https://akahn30.github.io/Prism-Ai/">Live Workspace</a> &nbsp;·&nbsp;
    <a href="#featured-projects">Projects</a> &nbsp;·&nbsp;
    <a href="https://dev.to/prismaidev">Dev.to</a> &nbsp;·&nbsp;
    <a href="https://www.reddit.com/r/PrismAIApp/">Reddit</a> &nbsp;·&nbsp;
    <a href="https://www.instagram.com/prismhq.ai/">Instagram</a>
  </p>
</div>

---

## Hi, I'm Aidan

I build practical software for research, technical writing, local AI, and developer workflows.

My projects share a common goal: keep you in control of your data, make complex tools approachable, and show what software is doing before it changes something important. That means bringing research and LaTeX writing into one workspace, checking generated outputs against explicit rules, and helping developers recover Git commits without disturbing their current work.

I work mostly in Python, Rust, and JavaScript, with a focus on local-first workflows, modular design, and clear documentation.

### Start Here

| I want to... | Project | Built With | Get Started |
| :--- | :--- | :--- | :--- |
| Research, organize notes, and write LaTeX with AI help | [Prism AI](https://github.com/akahn30/Prism-Ai) | JavaScript · LaTeX · Ollama | [Browser Workspace](https://akahn30.github.io/Prism-Ai/) · [Windows Releases](https://github.com/akahn30/Prism-Ai/releases) |
| Generate local AI outputs, verify them, and curate training data | [Prism Zero](https://github.com/akahn30/prism-zero) | Python · PyTorch · PEFT | [Quickstart](https://github.com/akahn30/prism-zero#quick-start) · [Validation Notes](https://github.com/akahn30/prism-zero/blob/main/VALIDATION.md) |
| Find earlier Git commits and save them to a branch | [git-panic](https://github.com/akahn30/git-panic) | Rust · Git Reflog | [Installation](https://github.com/akahn30/git-panic#installation) · [Usage Guide](https://github.com/akahn30/git-panic/blob/main/docs/guide.md) |

---

## Featured Projects

### [Prism AI](https://github.com/akahn30/Prism-Ai)
**Keep your research connected to your writing.**

<a href="https://github.com/akahn30/Prism-Ai">
  <img src="assets/prism-card.svg" alt="Prism AI: research and writing with Prism Chat and Prism Studio" width="100%">
</a>

A modular workspace that brings project notes, source materials, AI conversations, and LaTeX authoring into one place.

- **Prism Chat:** Organize multi-turn research threads, references, and Markdown notes within dedicated projects.
- **Prism Studio:** Write papers and presentations with LaTeX and BibTeX, with automatic PDF compilation via Tectonic.
- **Model choice:** Use local Ollama models, or configure optional cloud providers separately for Chat and Studio.

**Focus:** Connecting research organization, model integration, and document production, while keeping the difference between local and cloud features clear.

**Stack:** JavaScript · LaTeX / BibTeX · Ollama · Tectonic

[Repository](https://github.com/akahn30/Prism-Ai) · [Live Browser Workspace](https://akahn30.github.io/Prism-Ai/) · [Windows Releases](https://github.com/akahn30/Prism-Ai/releases)

<details>
<summary>Browser vs. desktop scope</summary>

The public repository hosts the browser workspace and documentation, not the full source for the packaged Windows apps. Features and setup requirements differ between the two environments.

</details>

---

### [Prism Zero](https://github.com/akahn30/prism-zero)
**Generate locally. Verify explicitly. Train deliberately.**

<a href="https://github.com/akahn30/prism-zero">
  <img src="assets/prism-zero-card.svg" alt="Prism Zero: generate locally, verify explicitly, curate examples, and train deliberately." width="100%">
</a>

An offline-first Python toolkit for local AI pipelines where generated outputs must pass defined checks before they become training examples.

1. **Generate:** Produce candidates from a local checkpoint or scripted baseline.
2. **Verify:** Check supported constraints, including JSON Schema validation, exact rational math, and symbolic rules.
3. **Curate:** Retry rejected candidates within a set budget and save the ones that pass.
4. **Fine-tune:** Inspect the curated dataset, then explicitly run local LoRA fine-tuning.

**Focus:** Separating generation from acceptance criteria, bounding retries, and making the path from candidate to training example inspectable.

**Stack:** Python · PyTorch · Pydantic · JSON Schema · PEFT / LoRA

[Repository](https://github.com/akahn30/prism-zero) · [Quickstart](https://github.com/akahn30/prism-zero#quick-start) · [Source](https://github.com/akahn30/prism-zero/tree/main/prism_zero) · [Validation Notes](https://github.com/akahn30/prism-zero/blob/main/VALIDATION.md)

<details>
<summary>What "verified" means</summary>

Passing a verifier means an output satisfies the implemented checks. It doesn't establish general factual correctness, completeness, or fitness for every use case.

</details>

---

### [git-panic](https://github.com/akahn30/git-panic)
**Find an earlier commit. Give it a branch. Decide what happens next.**

<a href="https://github.com/akahn30/git-panic">
  <img src="assets/git-panic-card.svg" alt="git-panic: find, preview, and preserve local Git commits." width="100%">
</a>

A focused Rust CLI, built while developing Prism AI, for recovering local Git commits. It lets you inspect before changing anything.

- **Search the reflog:** Find earlier or detached commits recorded in your local `HEAD` reflog.
- **Preview recovery:** Check target commit metadata and proposed branch names before creating anything.
- **Preserve the commit:** Create a recovery branch without switching branches or touching working files.

**Focus:** A small recovery workflow that separates inspection from action and keeps changes narrowly scoped.

**Stack:** Rust · Git Reflog · CLI

[Repository](https://github.com/akahn30/git-panic) · [Installation](https://github.com/akahn30/git-panic#installation) · [Beginner & AI Guide](https://github.com/akahn30/git-panic/blob/main/docs/guide.md)

<details>
<summary>Recovery limits</summary>

Recovery depends on the relevant commits still existing locally. Uncommitted edits and untracked files can't be recovered by this tool.

</details>

---

## What Connects My Projects

- **User control:** Local processing and optional external services are easy to tell apart.
- **Inspectable workflows:** Proposed actions and acceptance criteria are visible, not hidden.
- **Deliberate changes:** Recovery actions are previewed, retries are bounded, and training steps are explicit.
- **Practical delivery:** Setup instructions, guides, and limitations are part of the product.

---

## In Active Development

These are private for now, shared here as context:

- **FolderPilot** · Python · Windows: A review-first desktop file organizer. It previews destination mappings before moving anything, keeps local history, and supports checked undo.
- **Prism Web** · Python · SQLite: A full-stack prototype exploring Auth0 authentication, Stripe billing, and server-side AI orchestration.

---

## Tech Stack

| Area | Technologies |
| :--- | :--- |
| Languages | Python, Rust, JavaScript, HTML/CSS, PowerShell |
| APIs & Validation | FastAPI, Pydantic, JSON Schema |
| Local AI & Training | Ollama, PyTorch, Hugging Face PEFT, LoRA |
| Data | SQLite, JSONL datasets |
| Research & Writing | Markdown, LaTeX, BibTeX, Tectonic |
| Developer Tooling | Git, CLI development, Windows packaging |

[AI Essentials 2026 Certificate of Completion](https://github.com/akahn30/DudeSquad999/blob/main/ai-essentials-2026-certificate.pdf)

---

## Connect & Contribute

Start with a featured project, explore the available source, and read the docs for the decisions and limitations behind it. I share updates on [Dev.to](https://dev.to/prismaidev), [Reddit](https://www.reddit.com/r/PrismAIApp/), and [Instagram](https://www.instagram.com/prismhq.ai/).

Bug reports, documentation fixes, and focused pull requests are welcome in the [Prism AI issue tracker](https://github.com/akahn30/Prism-Ai/issues).
