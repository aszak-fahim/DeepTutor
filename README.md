Warning: truncated output (original token count: 23649)
Total output lines: 1011

Failed to create stream fd: Operation not permitted
Failed to create stream fd: Operation not permitted
Failed to create stream fd: Operation not permitted
<div align="center">

<p align="center"><img src="assets/figs/logo/color-full.png" alt="DeepTutor" width="480"></p>
<h1 align="center">DeepTutor: Lifelong Personalized Tutoring</h1>

<p align="center">
<a href="https://www.star-history.com/hkuds/deeptutor"><picture><source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;type=trending&amp;theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;type=trending" /><img alt="GitHub Trending Repository of the Day" src="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;type=trending" height="55" /></picture></a>&#32;<a href="https://trendshift.io/repositories/17099"><img src="https://trendshift.io/api/badge/trendshift/repositories/17099/daily" alt="HKUDS/DeepTutor | Trendshift" width="250" height="55"></a>&#32;<a href="https://www.star-history.com/hkuds/deeptutor"><picture><source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;theme=dark"><source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor"><img alt="Star History Rank" src="https://api.star-history.com/badge?repo=HKUDS/DeepTutor" width="185" height="55"></picture></a>
</p>

<p align="center">
  <a href="https://github.com/HKUDS/DeepTutor/releases/latest/download/Open-DeepTutor-MacOS-Apple-Silicon.dmg"><img alt="Download for macOS (Apple Silicon)" src="assets/figs/badges/download-macos-apple-silicon.svg" height="32"></a>&nbsp;
  <a href="https://github.com/HKUDS/DeepTutor/releases/latest/download/Open-DeepTutor-MacOS-Intel.dmg"><img alt="Download for macOS (Intel)" src="assets/figs/badges/download-macos-intel.svg" height="32"></a>&nbsp;
  <a href="https://github.com/HKUDS/DeepTutor/releases/latest/download/Open-DeepTutor-Windows-Setup.exe"><img alt="Download for Windows (x64)" src="assets/figs/badges/download-windows.svg" height="32"></a>&nbsp;
  <a href="https://deeptutor.info" target="_blank"><img alt="Docs — deeptutor.info" src="assets/figs/badges/docs.svg" height="32"></a>
</p>

<p align="center">
  <a href="README.md"><img alt="English" height="40" src="https://img.shields.io/badge/English-BCDCF7"></a>&nbsp;
  <a href="assets/README/README_CN.md"><img alt="简体中文" height="40" src="https://img.shields.io/badge/简体中文-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_TW.md"><img alt="繁體中文" height="40" src="https://img.shields.io/badge/繁體中文-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_JA.md"><img alt="日本語" height="40" src="https://img.shields.io/badge/日本語-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_ES.md"><img alt="Español" height="40" src="https://img.shields.io/badge/Español-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_FR.md"><img alt="Français" height="40" src="https://img.shields.io/badge/Français-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_AR.md"><img alt="Arabic" height="40" src="https://img.shields.io/badge/Arabic-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_RU.md"><img alt="Русский" height="40" src="https://img.shields.io/badge/Русский-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_HI.md"><img alt="Hindi" height="40" src="https://img.shields.io/badge/Hindi-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_PT.md"><img alt="Português" height="40" src="https://img.shields.io/badge/Português-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_TH.md"><img alt="Thai" height="40" src="https://img.shields.io/badge/Thai-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_PL.md"><img alt="Polski" height="40" src="https://img.shields.io/badge/Polski-CDCFD4"></a>
</p>

[![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square)](LICENSE) [![GitHub release](https://img.shields.io/github/v/release/HKUDS/DeepTutor?style=flat-square&color=brightgreen)](https://github.com/HKUDS/DeepTutor/releases) [![arXiv](https://img.shields.io/badge/arXiv-2604.26962-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2604.26962) [![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/eRsjPgMU4t) [![Feishu](https://img.shields.io/badge/Feishu-Group-00D4AA?style=flat-square&logo=feishu&logoColor=white)](./Communication.md) [![WeChat](https://img.shields.io/badge/WeChat-Group-07C160?style=flat-square&logo=wechat&logoColor=white)](https://github.com/HKUDS/DeepTutor/issues/78)

[Features](#-key-features) · [Get Started](#-get-started) · [Explore](#-explore-deeptutor) · [CLI](#%EF%B8%8F-deeptutor-cli--agent-native-interface) · [Ecosystem](#-ecosystem--eduhub--the-skills-community) · [Community](#-community)

</div>

## AI Teacher fork direction

This checkout is the starting point for a focused AI Teacher product built on the DeepTutor engine. The planning brief (`../AI_Teacher_DeepTutor_Analysis_and_Role_Plan.pdf`) recommends a mobile-first learner journey: a short diagnostic, guided practice that teaches through hints, and a progress report. Potential follow-on work includes curriculum-specific materials and assessments, localization, teacher/parent progress views, secure roles, and server-enforced plans and quotas. These are goals, not features currently delivered by this checkout. The learner group, subject, curriculum, language, deployment model, and pricing still need to be selected and validated.

This clone is on upstream `main` at `v1.7.3` (2026-11-16). The planning brief analyzed `v1.6.15` and recommends pinning that tag for a hackathon fork. Decide which baseline to keep before making product changes; the package and extension architecture changed in `v1.7.0`.

Start with the upstream [Get Started](#-get-started) guide below. For the project-specific plan and policies, see [Architecture](ARCHITECTURE.md), [Contributing](CONTRIBUTING.md#ai-teacher-fork-workflow), [Changelog](CHANGELOG.md), [Security](SECURITY.md), and [License summary](LICENSE.md). The authoritative upstream license remains [`LICENSE`](LICENSE).

---

> 🤝 **We're actively recruiting maintainers!** See the [Contributing Guide](CONTRIBUTING.md#join-the-team) for the roles, requirements and how to apply.

<div align="center">
<img src="assets/figs/web-dev/overview.png" alt="DeepTutor Home and workspace navigation" width="900">
</div>

### 📦 Releases

> **[2026.11.16]** [v1.7.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.7.3) — Flexible reading and book editing, richer search and agent connections, clearer learning records, and more reliable model streams and desktop upgrades.

<details>
<summary><b>Past releases (more than 1 week ago)</b></summary>

> **[2026.11.6]** [v1.7.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.7.2) — Complete desktop downloads, selected-text speech, easier model setup, Korean interface preview, NVIDIA NIM embeddings, and more reliable mastery, retrieval, and updates.

> **[2026.11.1]** [v1.7.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.7.1) — Desktop previews, broader localization, password changes, checked video lessons, Anki and calendar exports, more providers, and wide reliability improvements.

> **[2026.10.28]** [v1.7.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.7.0) — Modular installation, a refreshed learning workspace, block notebooks with Dito, narrated video lessons, resumable embedding checkpoints, and more reliable tutoring.

> **[2026.10.19]** [v1.6.15](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.15) — Reviewed learning-path changes, grouped assessments, bounded tutoring memory, reliable chat recovery, sturdier parsing, retrieval comparisons, and native Gemini speech.

> **[2026.10.8]** [v1.6.14](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.14) — Original-source visual practice, recoverable indexing, unified video Reading, scientific research tools, managed plugins, a learning journal, and provider setup improvements.

> **[2026.10.4]** [v1.6.13](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.13) — Reading and listening improvements, question-bank practice, resilient document parsing, configurable speech, workspace-visible attachments, Polish, and new providers.

> **[2026.9.27]** [v1.6.12](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.12) — Workspace KB moves, Kiwix archives, source figures, Task Board, German UI, and chat recovery.

> **[2026.9.24]** [v1.6.11](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.11) — French and Ukrainian interfaces, reading folders with in-chat selection actions, figures sent to vision models, paged Office previews, and self-syncing knowledge bases.

> **[2026.9.22]** [v1.6.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.10) — Native LightRAG role models, a published index that records and enforces what built it, PDF attachments that follow your parsing engine, visible truncation, and unfiltered provider choices.

> **[2026.9.21]** [v1.6.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.9) — Folder-based learning workspaces, daily practice, redesigned Settings, clearer streaming conversations, persistent usage accounting, and recoverable archives with explicit permanent deletion.

> **[2026.9.14]** [v1.6.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.8) — A recycle bin for deleted chats, search across your whole conversation history, a tool that looks past your knowledge base, and a sweep of fixes for quiet failures.

> **[2026.9.11]** [v1.6.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.7) — A fix release: books that arrived as one empty chapter, quizzes that produced nothing, the model's scratchpad in the text, formulas printed raw, and cards you could not submit.

> **[2026.9.8]** [v1.6.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.6) — A fix release: answers that could not submit, a copy button that lied, connected knowledge bases for partners, Codex sign-in inside Docker, and a 100 KB lighter home route.

> **[2026.9.6]** [v1.6.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.5) — A content workspace you point at any folder, one `exec` tool for every language, Mastery Path modes that gate its tools, and Settings that grades readiness.

> **[2026.9.3]** [v1.6.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.4) — Faster isolated runtimes, controllable Book generation, source-complete Mastery paths and Chat hand-offs, durable Reading, unified activity UI, recoverable sessions, and explicit per-model API capabilities.

> **[2026.9.2]** [v1.6.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.3) — Breaking front/back-end refactor, strict canonical routes and recoverable streams, plus learner/guardian accounts, grounded Reading, WeKnora, broader parsing, Python 3.14, and DashScope media.

> **[2026.8.31]** [v1.6.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.2) — Immersive YouTube learning, a plugin-driven Visualize catalog, three new agent harnesses, safer reading citations, multi-format MinerU, live Partner channel status, and guided updates.

> **[2026.8.30]** [v1.6.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.1) — One vendor key linked to every service it serves, a task model for background work, Settings as a searchable navigator, a sidebar you arrange, and first-party **LightRAG**.

> **[2026.8.27]** [v1.6.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.0) — Faithful EPUB reading and annotations, Courses with Little Tutor and Ask Questions, bounded web-source sync, shared Books with private learning state, and Serply/native search.

> **[2026.8.25]** [v1.5.17](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.17) — Partners each member owns with private conversations and linkable chat accounts, GitHub repos as a knowledge source, **Antigravity CLI**, browser WeChat QR login, and `deeptutor doctor`.

> **[2026.8.22]** [v1.5.16](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.16) — **MarginNote 4** libraries you connect and its add-on fills, Book pages that turn again, and tool-call ids, embeddings and temperature limits that stop breaking behind a gateway.

> **[2026.8.20]** [v1.5.15](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.15) — **PageIndex OSS** you host yourself with reasoning retrieval, a question bank you can finally file into, third-party tool/capability plugins, and **Apache Tika** parsing.

> **[2026.8.19]** [v1.5.14](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.14) — **Immersive Reading**: a document open beside the thread, cited page by page; DeepTutor configures itself from chat; IMA libraries you browse and write to; a notebook console.

> **[2026.8.17]** [v1.5.13](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.13) — Books stream while they compile, track your progress, and export to Markdown; a cost estimate before you approve a spine; and home starter suggestions drawn from memory.

> **[2026.8.13]** [v1.5.12](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.12) — Web search rebuilt with six new providers (**Doubao**, **Bocha**, **Zhipu**, **Firecrawl**, **Qianfan**, **Aliyun IQS**), a **LiteParse** parsing engine, MCP servers that reconnect on credential change, and **CodeBuddy** + **OrcaRouter**.

> **[2026.8.10]** [v1.5.11](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.11) — Prose around a DSML tool call stops vanishing, a truncated reply continues instead of ending, live memory usage in Settings, and LightRAG indexing off the event loop.

> **[2026.8.7]** [v1.5.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.10) — Every account signs in to its own **Codex**, model output language becomes its own setting, empty tool calls are rejected instead of retried, and uploads stop blocking the loop.

> **[2026.8.4]** [v1.5.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.9) — Gemini **Embedding 2** on its native endpoint, a per-model **reasoning effort** control, a **Novita AI** gateway, retrieval roles for queries, and Compose deployments that keep all of `data/`.

> **[2026.8.2]** [v1.5.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.8) — Memory: a real heap ceiling for the dev server, source installs serve a production build, bounded LLM client and index caches, and a keep-alive fix for stray 500s.

> **[2026.7.31]** [v1.5.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.7) — A per-account **MCP Services** store, 101 **CLI Apps** the tutor can run, credentials moved out of the sandbox's reach, and a mobile layout.

> **[2026.7.29]** [v1.5.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.6) — Remote **Codex** sign-in completes behind an SSH tunnel, generated files get their own card in Activity, non-English languages stop collapsing to Chinese, and book creation no longer times out.

> **[2026.7.26]** [v1.5.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.5) — Sign in with your ChatGPT plan via **OpenAI Codex** OAuth, an **Eden AI** provider, knowledge bases that report what they hold, traceable `rag` citations, and GraphRAG indexing without a workaround.

> **[2026.7.24]** [v1.5.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.4) — Maintenance sweep: the post-answer "generating" stall is gone, IM partners render Markdown tables faithfully, LLM JSON parsing is sturdier, plus quiz, create-KB form, and Math Animator fixes.

> **[2026.7.24]** [v1.5.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.3) — Themeable code blocks, four more coding CLIs in My Agents (Gemini, Kimi, opencode, MiMo), an Atlas Cloud LLM provider, and a broad chat, memory, embedding, and parsing reliability sweep.

> **[2026.7.19]** [v1.5.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.2) — Configurable chat attachment limits, PageIndex retrieval that reasons across your documents via agentic tool calls, broader Anthropic/OpenAI model support, and steadier Book, Knowledge Base, and chat UI.

> **[2026.7.9]** [v1.5.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.1) — Remove a single failed document from a knowledge base — even one stuck in an **error** state — instead of deleting and rebuilding the whole base.

> **[2026.7.4]** [v1.5.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.0) — LlamaIndex ingestion now honors your **Document Parsing** engine with multimodal image extraction, Partner & Soul ids stay URL-safe for non-Latin names, and optional RAG extras install cleanly on Python 3.14+.

> **[2026.6.30]** [v1.4.15](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.15) — A native **Mattermost** channel for Partners, plus fixes so Guided Learning multiple-choice questions grade correctly and a configured zero chunk overlap is honored.

> **[2026.6.29]** [v1.4.14](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.14) — Click an assigned partner to chat in one step, Deep Research flags partial reports, LightRAG indexes without MinerU, FAISS handles non-ASCII paths, and PocketBase sessions are isolated per user.

> **[2026.6.27]** [v1.4.13](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.13) — Partners support non-Latin names and become assignable to users, logos render after login (#599), tiny knowledge bases retrieve reliably, and containers start cleanly under rootless Podman.

> **[2026.6.24]** [v1.4.12](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.12) — A new **LightRAG Server** retrieval engine, a lightweight **PyMuPDF4LLM** parsing engine, and a FAISS vector backend that makes large knowledge-base retrieval dramatically faster.

> **[2026.6.23]** [v1.4.11](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.11) — Native tool calling on every cloud OpenAI-compatible provider, a redesigned admin Users page, LaTeX in quiz options, an honest session-loading spinner, and configurable container host binding.

> **[2026.6.21]** [v1.4.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.10) — A self-service **Profile** page with avatars, a rootless-ready container guide with a single-port request-time proxy, and deny-by-default MCP tools for non-admin users.

> **[2026.6.19]** [v1.4.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.9) — Settings polish: Search shows only the fields your provider needs, connection profiles can be renamed and auto-named by provider, and graded Mastery Path questions flow into your Question Bank.

> **[2026.6.18]** [v1.4.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.8) — Connect your own **Partners** under **My Agents** and consult them live in chat — answering through their own persona, library and skills — each with its own private memory.

> **[2026.6.18]** [v1.4.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.7) — Connect your local **Claude Code / Codex** and consult it live mid-turn, **My Agents** graduates to a top-level `/agents`, and Partner conversations gain branch / resume / delete with a replayable trace.

> **[2026.6.17]** [v1.4.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.6) — Four-surface consolidation: a Space learning dashboard with importable **My Agents** and top-level Memory, a **Knowledge Center** with GraphRAG / PageIndex / LightRAG / linked-KB / Obsidian, opened-up Settings, and per-model capability gating.

> **[2026.6.14]** [v1.4.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.5) — Guided Learning rebuilt on the chat agent loop with a hard per-type mastery gate and a `/learning` dashboard, a new loop-plugin framework, plus Markdown export / save-to-notebook for Partner conversations.

> **[2026.6.13]** [v1.4.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.4) — Install communi…13649 tokens truncated…ge exchanges the one-time code for an equally short JWE ticket in a POST body, consumes the ticket once, and receives the normal HttpOnly session cookie.

> PocketBase stays a single-user integration — keep `integrations.pocketbase_url` blank for multi-user deployments unless you've wired up an external user store.

</details>

## ⌨️ DeepTutor CLI — Agent-Native Interface

One `deeptutor` binary, two ways in: an interactive **REPL** for people who live in the terminal, and structured **JSON** for other agents that drive DeepTutor as a tool. Same capabilities, tools, and knowledge bases either way.

<details>
<summary><b>Drive it yourself</b></summary>

`deeptutor chat` opens an interactive REPL and selects a mode with `--capability`; `deeptutor run <capability> "<message>"` takes that capability as its first positional argument and exits after one turn. Both accept `--tool`, `--kb`, `--config`, and `--workspace` to select a registered workspace.

```bash
deeptutor chat                                              # interactive REPL
deeptutor chat --capability deep_solve --kb my-kb
deeptutor run chat "Explain the Fourier transform" --kb textbook
deeptutor run chat "Find recent work beyond this material" --kb textbook
deeptutor run deep_research "Survey 2026 papers on RAG" \
  --config mode=report --config depth=standard
```

`--kb` supplies context for automatic RAG and Knowledge Frontier tools; Frontier needs both knowledge and research modules. `--tool` selects user-toggleable tools. Enabled modules also provide KB, session, partner, skill, notebook, memory, and config commands.

</details>

<details>
<summary><b>Let an agent drive it</b></summary>

DeepTutor is built to be *operated by another agent*. Add `--format json` to any `run` and each turn streams **NDJSON — one event per line** (`content`, `tool_call`, `tool_result`, `done`, …), every line tagged with its `session_id`. Runs are headless-safe: an `ask_user` pause with no TTY auto-resolves with an empty reply instead of hanging.

```bash
# One shot, machine-readable
deeptutor run deep_solve "Find d/dx[sin(x^2)]" --tool reason --format json

# Chain turns in one stateful session — capture the id, reuse it
SID=$(deeptutor run deep_research "Survey 2026 papers on RAG" \
  --config mode=report --config depth=standard --format json \
  | jq -r 'select(.type=="done").session_id')
deeptutor run deep_question "Quiz me on that survey" --session "$SID" --format json
```

The repo ships a root [`SKILL.md`](SKILL.md) — a compact handover doc for the CLI. Ask your agent to read it explicitly; its [Agent Setup guide](docs-for-dev/AGENT_SETUP.md) covers installation and configuration. You can also wrap `deeptutor run` as a tool in a LangChain / AutoGen loop. Full recipes: [Agent Handoff](https://deeptutor.info/docs/cli/agent-handoff/).

</details>

<details>
<summary><b>Opt-in visual review for Manim animations</b></summary>

Set `enable_visual_review=true` to inspect rendered frames for overlap, readability,
and framing, then feed detected issues into the existing code repair loop:

```bash
deeptutor run math_animator "Animate a sine wave" --config enable_visual_review=true
deeptutor run visualize "Animate a sine wave" \
  --config render_mode=manim_video --config enable_visual_review=true
```

The option defaults to `false`. It also works with `output_mode=image` for
`math_animator` and `render_mode=manim_image` for `visualize`. Other visualizers,
including the general `auto` loop, ignore it. Manim's optional dependencies are
still required.

For SDK turns, pass `config={"enable_visual_review": True}` in the `TurnRequest`
sent to `DeepTutorApp.start_turn()`. API clients use the same `config` object with
JSON `true`. For book animation blocks, set
`params={"enable_visual_review": True}` on the animation `Block`.

Review adds vision model calls and may add repair calls and re-renders, increasing
cost and latency. It uses the existing limit of four retries, with a 120-second
review timeout and a 180-second repair timeout. If no frames are available or the
configured review model cannot inspect images, review is skipped with a summary.
An unsuccessful review after all retries returns the best available render and its
failed review result; a review timeout follows the existing render error/retry path.
Capability results expose `render.visual_review`; book blocks retain the same
review data in `metadata.visual_review` (`null` when review did not run).

</details>

<details>
<summary><b>Command reference</b></summary>

The table covers the full installation and optional add-ons; commands and capabilities require their modules to be enabled. Core provides `chat` and `ask_questions`.

| Command | Description |
|:---|:---|
| `deeptutor init [--non-interactive] [--home PATH]` | Run the setup wizard, or create missing defaults without prompts |
| `deeptutor doctor [--online]` | Check whether the runtime is ready to start a session; `--online` also probes the configured model provider, `--format json` prints the report |
| `deeptutor start [--home PATH] [--dev] [--detach] [--no-browser]` | Launch backend + frontend together; optionally detach or suppress browser opening |
| `deeptutor stop [--home PATH]` | Stop a launcher started with `--detach` |
| `deeptutor serve [--port PORT]` | Start only the FastAPI backend |
| `deeptutor module list/install/uninstall/enable/disable` | Inspect modules and change them with DeepTutor stopped; source checkouts support enable/disable |
| `deeptutor workspace show/set/reset` | Inspect, select, or restore the per-user Content Workspace |
| `deeptutor run <capability> <message>` | Run a single capability turn (`chat`, `ask_questions`, `deep_solve`, `deep_question`, `deep_research`, `visualize`, `math_animator`, `video_lesson`, `mastery_path`, `immersive_reading`, `audio_overview`); add `--format json` for NDJSON output |
| `deeptutor chat` | Interactive REPL with capability, tool, KB, notebook, and history controls |
| `deeptutor partner list/create/start/stop` | Manage IM-connected partners |
| `deeptutor kb list/info/create/connect-kiwix/add/search/eval/eval-diff/set-default/delete/list-sources/sync` | Manage knowledge bases, connect Kiwix archives, score and compare retrieval runs, and synchronize registered GitHub/web sources (with source add/remove commands) |
| `deeptutor skill search/install/list/remove/login/logout/publish/update` | Manage skills, install from hubs, and publish your own (`eduhub:<slug>` by default, see Ecosystem) |
| `deeptutor memory show/clear` | Inspect L2/L3 memory docs or clear L1/all memory |
| `deeptutor session list/show/open/rename/delete` | Manage shared sessions |
| `deeptutor notebook list/create/show/add-md/replace-md/remove-record` | Manage notebooks from Markdown files |
| `deeptutor book list/health/refresh-fingerprints` | Inspect books and refresh source fingerprints |
| `deeptutor plugin list/info/state/search/show/install/approve/enable/disable/rollback/uninstall` | Inspect tools and capabilities; manage reviewed plugin packages and their permission approvals |
| `deeptutor config show [--home PATH]` | Show resolved runtime configuration with credentials redacted |
| `deeptutor config providers` | List supported setup providers and defaults as JSON |
| `deeptutor config apply FILE [--check] [--home PATH]` | Apply setup JSON without prompts, or validate it without writing settings |
| `deeptutor provider login <provider>` | Provider auth (`openai-codex` OAuth login; `github-copilot` GitHub device login; `codebuddy` validates CodeBuddy SDK auth and starts login when needed) |

GitHub Copilot credentials belong to the signed-in DeepTutor owner and live only at
`<runtime-home>/data/system/user-secrets/<owner-id>/private/github-copilot/credentials.v1.json`,
outside sandbox workspaces. CLI/admin partners use the administrator's credentials;
other users sign in separately, and Copilot profiles cannot be shared through model grants.
External nanobot/Copilot token files are never imported: after upgrading, run
`deeptutor provider login github-copilot` again.

Login validates inference with a currently discovered model; `init` validates the selected
model and aborts on failure without saving the draft configuration. Successful GitHub
authentication alone does not establish Copilot model access (the saved login is retained
if validation fails). Runtime requests follow the API endpoint returned by token exchange,
including refreshes, and respect each model's Responses/Chat Completions endpoint metadata.

Copilot-specific Responses compatibility is applied at dispatch without rewriting stored history.

</details>

<details>
<summary><b>CLI-only distribution</b></summary>

The core wheel supplies CLI and SDK; `deeptutor-cli` is a compatibility metapackage. Source exposes all checked-in modules, so install their Python dependencies and skip frontend setup for CLI use:

```bash
python -m pip install -r requirements/full.txt
python -m pip install -e . --no-deps
```

For a minimal installation, use the core wheel. Optional distributions contribute tools, capabilities, API routes, background services, and navigation. Modules share one Python environment and must match the core version. `deeptutor[full]` selects the common app modules at installation; individual features can still be removed later.

Stop DeepTutor (`Ctrl+C` in its terminal), then use the same Python environment and `DEEPTUTOR_HOME`:

```bash
deeptutor module list                       # installed / enabled / ready
deeptutor module disable research           # hide and deactivate; keep code
deeptutor module enable research            # restore it and required modules

# Package installations only; source checkouts use enable / disable:
deeptutor module install solve              # install the matching module and dependencies
deeptutor module uninstall solve --dry-run  # inspect the plan and dependency blockers
deeptutor module uninstall solve            # remove only this module's distribution
deeptutor chat                              # restart the CLI; use start for an installed Web app
```

Examples: `solve`, `research`, `questions`, `knowledge`, `parsing`, `reading`, `mastery`, `books`, `memory`, `notebook`, and `partners`. Dependents block removal; core cannot be removed through the module command. Disabling or uninstalling preserves settings, conversations, knowledge bases, and generated files. Shared third-party dependencies are retained.

**In the browser:** **Settings → Runtime status → Modules** shows module status and the corresponding terminal commands. Package changes require a stopped environment and are performed in the CLI. **Chat → Customize page** and **Learning → New learning activity → Customize page** change personal page choices immediately; hiding an entry does not uninstall its module or revoke access.

The 1.7.0 package family uses matching versions across core and feature wheels. For local wheel installation, pass `--wheelhouse /path/to/wheels` to `module install`. See [module installation and source development](docs-for-dev/MODULES.md) for building the wheels and deployment details.

</details>

## 🧩 Ecosystem — EduHub & the Skills Community

DeepTutor skills use the open **Agent-Skills** format — a folder with a `SKILL.md` playbook (YAML frontmatter + Markdown) and optional reference files. Nothing about it is DeepTutor-specific, so any registry that speaks the format becomes a source for your library. DeepTutor ships with **[EduHub](https://eduhub.deeptutor.info/)** — our own education-focused skill registry — wired in as the default hub.

<details>
<summary><b>EduHub — DeepTutor's skill ecosystem</b></summary>

[**EduHub**](https://eduhub.deeptutor.info/) is the community hub DeepTutor launched for sharing teaching-oriented agent skills — Socratic tutors, flashcard builders, essay feedback, exam blueprints, concept explainers, and more. It is built into DeepTutor, so there's nothing to configure: a bare slug or an `eduhub:` prefix resolves to it.

**Find and install** — in the browser, open **Personalization → Skills → Import from EduHub** to browse the catalog and download a skill straight into your library. From the terminal:

```bash
deeptutor skill search "socratic tutor"               # search EduHub (the default hub)
deeptutor skill install socratic-tutor                # fetch → verify → register
deeptutor skill install eduhub:socratic-tutor@1.2.0   # pin a hub and a version
deeptutor skill list                                  # local skills with their hub provenance
```

**Publish your own** — package a `SKILL.md` and share it back to the community:

```bash
deeptutor skill login                                 # browser sign-in to EduHub
deeptutor skill publish ./my-skill                    # interactive: pick a track + tags, then upload
deeptutor skill update                                # roll back or release a new version
```

EduHub is also a standalone, ClawHub-compatible registry, so agents that aren't DeepTutor (Claude Code, Codex, …) can use it directly through the `eduhub` CLI — `npx eduhub install socratic-tutor`.

</details>

<details>
<summary><b>The import safety gate</b></summary>

Whatever the source, every import passes the **same safety gate** before anything touches your workspace:

- the registry's **security verdict** is checked first — flagged packages are refused unless you pass `--allow-unverified`;
- archives are extracted defensively with path-traversal, entry-count, size, compression-ratio, suffix, and symlink checks; executable bits are stripped, while extensionless files remain allowed;
- frontmatter is normalized to DeepTutor's schema and `always:` is **stripped**, so a downloaded skill can never force itself into every system prompt;
- provenance — hub, version, verdict, and install time — is written to `.hub-lock.json` for audits and updates.

In multi-user deployments, browser imports land in the authenticated caller's skill layer, while CLI and admin-console installs target the owner/admin workspace; admin skills stay hidden and read-only for ordinary users until granted.

</details>

<details>
<summary><b>Also compatible with ClawHub</b></summary>

Because DeepTutor speaks the open Agent-Skills format, **[ClawHub](https://clawhub.ai/)** works as a first-class source too — it's built in alongside EduHub. Pick it with the hub prefix:

```bash
deeptutor skill search "git release notes" --hub clawhub
deeptutor skill install clawhub:git-release-notes@1.0.1
deeptutor skill install clawhub:udiedrichsen/stock-analysis
```

When several publishers share the same slug, search shows each publisher and a
fully scoped install ref (`clawhub:<ownerHandle>/<slug>`).

Add more registries in `data/user/settings/skill_hubs.json`: a `type: "clawhub"` entry points at any compatible HTTP API (EduHub and ClawHub both speak it), `type: "command"` wraps whatever fetch CLI a registry ships, and `"default"` chooses the hub used for bare slugs. All of them feed the same import gate.

</details>

## 🤝 Open Source Partners

<p align="center">
  <a href="https://github.com/VectifyAI/PageIndex" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/figs/partners/pageindex-mark-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/figs/partners/pageindex-mark.svg">
      <img src="assets/figs/partners/pageindex-mark.svg" alt="PageIndex" height="38">
    </picture>
  </a>
</p>

<p align="center">
  Using code: <b><code>DEEPTUTOR20</code></b> — get $20 off for your first <a href="https://developer.pageindex.ai/">PageIndex subscription</a>!
</p>

## 🌐 Community

### 🔗 Maintainers

<table>
  <tr>
    <td align="center"><a href="https://github.com/pancacake"><img src="https://avatars.githubusercontent.com/u/150592536?v=4&s=80" width="80" height="80" alt="Bingxi Zhao"><br><strong>Bingxi Zhao</strong></a></td>
    <td align="center"><a href="https://github.com/TyrionH-is-coding"><img src="https://avatars.githubusercontent.com/u/275607548?v=4&s=80" width="80" height="80" alt="Xingyu Hou"><br><strong>Xingyu Hou</strong></a></td>
    <td align="center"><a href="https://github.com/zzhtx258"><img src="https://avatars.githubusercontent.com/u/175302980?v=4&s=80" width="80" height="80" alt="Jiahao Zhang"><br><strong>Jiahao Zhang</strong></a></td>
  </tr>
</table>

### 📮 Contact

DeepTutor is an open-source project led by [Bingxi Zhao](https://github.com/pancacake) within the [HKUDS](https://github.com/HKUDS) Group, and it iterates in a **fully open-source form**, built together with the community. So far, we **DO NOT** have paid online products of any form. Feel free to reach out at **bingxizhao39@gmail.com** for discussions, ideas, or collaboration.

### 🙏 Appreciation

Heartfelt thanks to [**Chao Huang**](https://sites.google.com/view/chaoh), director of the Data Intelligence Lab @ HKU, and to our HKUDS labmates for their warm support — especially [**Jiahao Zhang**](https://github.com/zzhtx258), [**Zirui Guo**](https://github.com/LarFii), and [**Xubin Ren**](https://github.com/Re-bin). We're also deeply grateful to the **open-source community**: your stars, issues, pull requests, and discussions shape DeepTutor every single day.

DeepTutor also stands on the shoulders of outstanding open-source projects that gave us both tools and inspiration:

| Project | Role / Inspiration |
|:---|:---|
| [**LlamaIndex**](https://github.com/run-llama/llama_index) | RAG pipeline and document-indexing backbone |
| [**nanobot**](https://github.com/HKUDS/nanobot) | Ultra-lightweight agent engine that powered the original TutorBot *(HKUDS)* |
| [**LightRAG**](https://github.com/HKUDS/LightRAG) | Simple & fast RAG *(HKUDS)* |
| [**AutoAgent**](https://github.com/HKUDS/AutoAgent) | Zero-code agent framework *(HKUDS)* |
| [**AI-Researcher**](https://github.com/HKUDS/AI-Researcher) | Automated research pipeline *(HKUDS)* |
| [**OpenClaw**](https://github.com/openclaw/openclaw) | Open agent gateway and skill ecosystem behind ClawHub |
| [**Codex**](https://github.com/openai/codex) | Agent-native coding CLI that inspired our CLI workflow |
| [**Claude Code**](https://github.com/anthropics/claude-code) | Agentic coding CLI that inspired the DeepTutor agent loop |
| [**ManimCat**](https://github.com/Wing900/ManimCat) | AI-driven math animation generation for Math Animator |

### 🗺️ Roadmap & Contribute

We want DeepTutor to keep iterating and improving — and ultimately to become a gift we give back to the open-source community. Our [**roadmap**](https://github.com/HKUDS/DeepTutor/issues/498) is updated continuously; vote on items there or propose new ones. If you'd like to contribute, see the [**Contributing Guide**](CONTRIBUTING.md) for branching strategy, coding standards, and how to get started.

<div align="center">

We hope DeepTutor becomes a gift for the community. 🎁

See the [development-branch contributor list](CONTRIBUTORS.md) for recently integrated contributions.

<a href="https://github.com/HKUDS/DeepTutor/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=HKUDS/DeepTutor&max=999" alt="Contributors" />
</a>

</div>

<p align="center">
 <a href="https://www.star-history.com/hkuds/deeptutor">
  <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor" />
   <img alt="Star History Rank" src="https://api.star-history.com/badge?repo=HKUDS/DeepTutor" />
  </picture>
 </a>
</p>

<div align="center">

Licensed under the [Apache License 2.0](LICENSE).

<p>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=HKUDS.DeepTutor&style=for-the-badge&color=00d4ff" alt="Views">
</p>

</div>
