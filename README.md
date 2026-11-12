<div align="center">
  <img src="assets/profile-header.svg" alt="Hi, I'm Aidan. I build tools for research, writing, and code." width="100%">
  <p>Research and writing. Local AI experiments. Tools for developers.</p>
  <p>
    <a href="#find-your-project">Explore projects</a> ·
    <a href="https://dev.to/prismaidev">Development notes</a> ·
    <a href="#connect-and-contribute">Connect</a>
  </p>
</div>

## Hi, I'm Aidan

I'm the developer behind Prism AI, Prism Zero, and git-panic. I build tools that help people organize research, experiment with local AI, and work through Git recovery with an explicit preview-first workflow.

These projects solve different problems. Pick the one that fits what you want to do.

## Find your project

| I want to… | Start here | First step |
| :--- | :--- | :--- |
| Organize research and write with AI | [Prism AI](https://github.com/DudeSquad999/Prism-Ai) | [Explore the browser workspace](https://dudesquad999.github.io/Prism-Ai/) or [see Windows releases](https://github.com/DudeSquad999/Prism-Ai/releases) |
| Verify generated outputs and experiment with local LoRA training | [Prism Zero](https://github.com/DudeSquad999/prism-zero) | [Run the scripted quickstart](https://github.com/DudeSquad999/prism-zero#quick-start) |
| Find and preserve an earlier Git commit | [git-panic](https://github.com/DudeSquad999/git-panic) | [Read the installation guide](https://github.com/DudeSquad999/git-panic#installation) |

## Prism AI

<a href="https://github.com/DudeSquad999/Prism-Ai">
  <img src="assets/prism-card.svg" alt="Prism AI: research and writing with Prism Chat and Prism Studio" width="100%">
</a>

A research and writing workspace for bringing questions, source material, notes, and drafts together.

- Prism Chat: organize conversations, sources, and Markdown notes into projects.
- Prism Studio: work on LaTeX papers and presentations, BibTeX references, and PDF compilation with Tectonic.
- Model choices: use local Ollama models or configure your own supported cloud-provider API key. Chat and Studio have separate configuration.

[Repository](https://github.com/DudeSquad999/Prism-Ai) · [Windows releases](https://github.com/DudeSquad999/Prism-Ai/releases) · [Installation guide](https://github.com/DudeSquad999/Prism-Ai/blob/Main/docs/installation.md) · [Browser workspace](https://dudesquad999.github.io/Prism-Ai/)

<details>
<summary>Before you try Prism AI</summary>

Prism AI is early-stage software. Review important AI-generated claims and citations. The browser workspace can connect to local Ollama for live chat; without Ollama, Chat uses labeled sample responses. It does not replace the Windows apps or include live web search, citation verification, or document uploads.

The public repository contains the browser workspace and project documentation, not the complete source for the packaged Windows apps. Cloud requests send included content to the configured provider; local inference does not mean every feature works offline.

</details>

## Prism Zero

<a href="https://github.com/DudeSquad999/prism-zero">
  <img src="assets/prism-zero-card.svg" alt="Prism Zero: generate locally, verify explicitly, curate examples, and train deliberately. Illustrative project card, not benchmark output." width="100%">
</a>

An offline-first Python toolkit for exploring a deliberate local AI workflow:

1. Generate a candidate with a scripted demo or trusted local checkpoint.
2. Verify it against explicit constraints, such as JSON Schema or exact rational arithmetic.
3. Retry rejected candidates within a fixed budget and curate accepted examples.
4. Review the dataset, then explicitly run local LoRA supervised fine-tuning.

No hosted model API is required. Model weights and optional ML dependencies are separate.

[Repository](https://github.com/DudeSquad999/prism-zero) · [Quickstart](https://github.com/DudeSquad999/prism-zero#quick-start) · [Source code](https://github.com/DudeSquad999/prism-zero/tree/main/prism_zero) · [Validation notes](https://github.com/DudeSquad999/prism-zero/blob/main/VALIDATION.md)

Passing a configured check is not proof of general correctness. Retrying a prompt does not update weights, and a successful training run does not establish improved model quality.

## git-panic

<a href="https://github.com/DudeSquad999/git-panic">
  <img src="assets/git-panic-card.svg" alt="git-panic: find, preview, and preserve local Git commits. Decorative terminal artwork, not command output." width="100%">
</a>

Find an earlier commit. Give it a branch. Decide what happens next.

I started git-panic after dealing with Git recovery while building Prism AI. It is a local recovery CLI written in Rust.

- Find commits by browsing or searching the local HEAD reflog.
- Preview the target commit and proposed branch name before writing.
- Explicitly create a new branch without switching branches or changing working files.

[Repository](https://github.com/DudeSquad999/git-panic) · [Installation](https://github.com/DudeSquad999/git-panic#installation) · [Beginner and AI-assistant guide](https://github.com/DudeSquad999/git-panic/blob/main/docs/guide.md)

This is not an automatic undo button. A recovery branch preserves an available commit, not uncommitted edits or untracked files.

## All public repositories

| Repository | Purpose |
| :--- | :--- |
| [Prism-Ai](https://github.com/DudeSquad999/Prism-Ai) | Research and writing workspace, browser application, and project documentation. |
| [prism-zero](https://github.com/DudeSquad999/prism-zero) | Candidate verification, accepted-example curation, and explicit local LoRA training. |
| [git-panic](https://github.com/DudeSquad999/git-panic) | Local Git commit discovery and preview-first branch preservation. |
| [DudeSquad999](https://github.com/DudeSquad999/DudeSquad999) | This profile README, SVG artwork, and profile resources. |

[Browse repositories on GitHub](https://github.com/DudeSquad999?tab=repositories)

## What connects my projects

I care about clear interfaces, useful AI tools, explicit user choices, and documentation that helps people get started. The projects are separate: you do not need Prism AI to use Prism Zero or git-panic.

## Learning

[AI Essentials 2026 certificate of completion](https://github.com/DudeSquad999/DudeSquad999/blob/main/ai-essentials-2026-certificate.pdf)

## Connect and contribute

Bug reports, reproducible examples, documentation feedback, and focused contributions are welcome. Read each project's contribution guidelines before proposing a change.

[Prism AI issues](https://github.com/DudeSquad999/Prism-Ai/issues) · [Prism Zero issues](https://github.com/DudeSquad999/prism-zero/issues) · [git-panic issues](https://github.com/DudeSquad999/git-panic/issues)

[Development notes](https://dev.to/prismaidev) · [Instagram](https://www.instagram.com/prismhq.ai/) · [Reddit community](https://www.reddit.com/r/PrismAIApp/)

Please keep API keys, passwords, private research, and personal information out of public issues. Use each project's security guidance for suspected vulnerabilities.

<details>
<summary>Privacy and project limitations</summary>

- Check each repository's current documentation, tests, and release notes before relying on a feature. This profile is an overview, not a validation report.
- Local tools used through a cloud-backed assistant do not make the assistant session offline. Review what data is sent to its provider.
- Git edits that were never stored, expired reflogs, and pruned objects may be unrecoverable.
- Prism Zero's verifiers check configured constraints; they are not a sandbox or a general proof of reasoning.
- The project cards are illustrative artwork, not screenshots or performance results.

</details>
