<div align="center">
  <h1>Hi, I'm Aidan.</h1>
  <p>Independent developer building research, writing, and developer tools.</p>
  <p>
    <a href="#what-im-building">Projects</a> ·
    <a href="https://dev.to/prismaidev">Development notes</a> ·
    <a href="#connect-and-share-feedback">Connect</a>
  </p>
</div>

## What I'm building

I build tools to make complicated workflows easier to navigate—from organizing research to finding a Git commit after something goes wrong.

| Project | What it helps you do | Start here |
| :--- | :--- | :--- |
| [Prism AI](https://github.com/DudeSquad999/Prism-Ai) | Research and write with Markdown, LaTeX, and local or cloud AI. | [Windows release](https://github.com/DudeSquad999/Prism-Ai/releases/tag/v3.1.0) · [Browser preview](https://dudesquad999.github.io/Prism-Ai/) |
| [git-panic](https://github.com/DudeSquad999/git-panic) | Find an earlier local Git commit and preserve it on a new branch. | [Install](https://github.com/DudeSquad999/git-panic#install) · [Beginner guide](https://github.com/DudeSquad999/git-panic/blob/main/docs/guide.md) |

## Prism AI

<a href="https://github.com/DudeSquad999/Prism-Ai">
  <img src="https://raw.githubusercontent.com/DudeSquad999/Prism-Ai/Main/prism-banner.png" alt="Prism AI — a workspace for research and writing" width="100%">
</a>

An early-stage Windows workspace that brings research and writing together in two companion apps.

- Prism Chat: explore questions and organize conversations, sources, and Markdown notes into projects.
- Prism Studio: draft LaTeX papers and presentations, review proposed edits, manage references, and compile PDFs.
- Model choice: use local models through Ollama, or connect your own Google Gemini, Anthropic, or OpenAI API key.

[Download Prism AI 3.1.0](https://github.com/DudeSquad999/Prism-Ai/releases/tag/v3.1.0) · [Installation guide](https://github.com/DudeSquad999/Prism-Ai/blob/Main/docs/installation.md) · [Explore the code](https://github.com/DudeSquad999/Prism-Ai)

The browser preview uses fixed examples; it does not connect to AI models or replace the Windows apps.

## git-panic

> Find an earlier commit. Give it a branch. Decide what happens next.

A local Git recovery helper written in Rust for developers and shell-capable coding assistants. It grew out of my recovery experience while building Prism AI.

1. Inspect the local HEAD reflog in a terminal timeline, or search it with literal text.
2. Preview a target commit and a proposed branch name without writing changes.
3. Explicitly create a new branch to preserve the commit—without switching branches or replacing working files.

[Explore the code](https://github.com/DudeSquad999/git-panic) · [Install and get started](https://github.com/DudeSquad999/git-panic#install) · [Beginner and AI-assistant guide](https://github.com/DudeSquad999/git-panic/blob/main/docs/guide.md)

It is not an automatic undo button. Preserving a commit and restoring working files are separate steps.

## Behind the projects

I'm interested in thoughtful interfaces, practical AI workflows, and making tools easier to understand—not just adding more features.

My current focus:

- Improving Prism's onboarding, workflows, and documentation.
- Sharing practical demonstrations of research and writing tasks.
- Using feedback to find confusing interactions and rough edges.

Learning: [AI Essentials 2026 — certificate of completion](https://github.com/DudeSquad999/DudeSquad999/blob/main/ai-essentials-2026-certificate.pdf).

## Connect and share feedback

Found something confusing? Tell me what you tried, what you expected, and what happened.

[Prism AI issues](https://github.com/DudeSquad999/Prism-Ai/issues) · [git-panic issues](https://github.com/DudeSquad999/git-panic/issues)

[Development notes](https://dev.to/prismaidev) · [Instagram](https://www.instagram.com/prismhq.ai/) · [Reddit community](https://www.reddit.com/r/PrismAIApp/)

Please keep API keys, passwords, private research, and personal information out of public issues.

<details>
<summary>Project limitations and privacy notes</summary>

- Prism AI is early-stage software. Check important AI-generated claims and citations.
- Local inference runs on your computer after setup, but some features need internet access. Cloud requests send included content to your configured provider.
- git-panic searches the local HEAD reflog. Edits Git never saved, expired reflogs, and pruned objects may be unrecoverable.
- git-panic does not automatically restore working files. A recovery branch is not a backup of uncommitted edits or untracked files.
- Using a local CLI through a cloud-backed assistant does not make the assistant session offline; review what output is sent to its provider.

</details>
