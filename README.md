<div align="center">
  <h1>Hi, I'm Aidan.</h1>
  <p>I build tools for research, writing, and working with code.</p>
  <p>
    <a href="#what-im-building">Projects</a> ·
    <a href="https://dev.to/prismaidev">Development notes</a> ·
    <a href="#connect-and-share-feedback">Connect</a>
  </p>
</div>

## What I'm building

I'm an independent developer building Prism AI and git-panic. One helps bring research and writing together. The other helps you find and preserve an earlier Git commit when something goes wrong.

| Project | What it does | Get started |
| :--- | :--- | :--- |
| [Prism AI](https://github.com/DudeSquad999/Prism-Ai) | A Windows workspace for research, Markdown notes, and LaTeX writing with local or cloud AI. | [Download](https://github.com/DudeSquad999/Prism-Ai/releases/tag/v3.1.0) · [Browser preview](https://dudesquad999.github.io/Prism-Ai/) |
| [git-panic](https://github.com/DudeSquad999/git-panic) | A Rust CLI for finding local Git commits and preserving them on new branches. | [Install](https://github.com/DudeSquad999/git-panic#install) · [Beginner guide](https://github.com/DudeSquad999/git-panic/blob/main/docs/guide.md) |

## Prism AI

<a href="https://github.com/DudeSquad999/Prism-Ai">
  <img src="https://raw.githubusercontent.com/DudeSquad999/Prism-Ai/Main/prism-banner.png" alt="Prism AI: a workspace for research and writing" width="100%">
</a>

Keep your research organized and turn it into writing. Prism AI is an early-stage Windows workspace with two companion apps.

- Prism Chat: explore questions and organize conversations, sources, and Markdown notes into projects.
- Prism Studio: draft LaTeX papers and presentations, review proposed edits, manage references, and compile PDFs.
- Use local models through Ollama, or connect your own Google Gemini, Anthropic, or OpenAI API key.

[Download Prism AI 3.1.0](https://github.com/DudeSquad999/Prism-Ai/releases/tag/v3.1.0) · [Installation guide](https://github.com/DudeSquad999/Prism-Ai/blob/Main/docs/installation.md) · [Source code](https://github.com/DudeSquad999/Prism-Ai)

The browser preview uses fixed examples. It does not connect to AI models or replace the Windows apps.

## git-panic

> Find an earlier commit. Give it a branch. Decide what happens next.

I started git-panic after dealing with Git recovery while building Prism AI. It is a local recovery helper written in Rust for developers and coding assistants that can run shell commands.

1. Find a commit by browsing the local HEAD reflog or searching its messages.
2. Preview the commit and your proposed branch name without making changes.
3. Explicitly create a new branch to preserve the commit. Your current branch and working files stay unchanged.

[Source code](https://github.com/DudeSquad999/git-panic) · [Installation](https://github.com/DudeSquad999/git-panic#install) · [Beginner and AI-assistant guide](https://github.com/DudeSquad999/git-panic/blob/main/docs/guide.md)

This is not an automatic undo button. Preserving a commit does not restore your working files.

## What I'm working on

I care about clear interfaces, useful AI tools, and documentation that helps people get started.

- Making Prism's setup and everyday workflows easier to follow.
- Sharing practical examples of research and writing tasks.
- Using feedback to improve confusing interactions and rough edges.

## Learning

[AI Essentials 2026 certificate of completion](https://github.com/DudeSquad999/DudeSquad999/blob/main/ai-essentials-2026-certificate.pdf)

## Connect and share feedback

Found a bug or a confusing step? Open an issue with what you tried, what you expected, and what happened.

[Prism AI issues](https://github.com/DudeSquad999/Prism-Ai/issues) · [git-panic issues](https://github.com/DudeSquad999/git-panic/issues)

[Development notes](https://dev.to/prismaidev) · [Instagram](https://www.instagram.com/prismhq.ai/) · [Reddit community](https://www.reddit.com/r/PrismAIApp/)

Please keep API keys, passwords, private research, and personal information out of public issues.

<details>
<summary>Project limitations and privacy notes</summary>

- Prism AI is early-stage software. Check important AI-generated claims and citations.
- Local inference runs on your computer after setup, but some features need internet access. Cloud requests send included content to your configured provider.
- git-panic searches the local HEAD reflog. Edits Git never saved, expired reflogs, and pruned objects may be unrecoverable.
- git-panic does not automatically restore working files. A recovery branch is not a backup of uncommitted edits or untracked files.
- Running a local CLI through a cloud-backed assistant does not make the session offline. Review what output the assistant sends to its provider.

</details>
