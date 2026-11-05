# Ablation Lab

Open research into how AI agents work, review and fail, plus the tools built along the way.

## Research

**[Evolving Review Councils](https://github.com/Ablation-Lab/evolving-review-councils)**

Do councils of AI reviewer agents beat one agent at the same cost, and can they evolve to get better? Plan, pilot notes and open questions, all published as the work happens.

**[Human in the Loop](https://github.com/Ablation-Lab/human-in-the-loop)**

When AI agents can talk to each other directly, what does keeping a human in the middle actually buy you? The plan, with the hypotheses and how results are measured, is published in the repo.

**[Research Framework](https://github.com/Ablation-Lab/research-framework)**

A lightweight template for keeping a research project on one core question: every new idea is either linked back to it or parked, with a research map, an evidence log and a claims ledger.

## Claude plugins and skills

| Tool | What it does | Platform |
| --- | --- | --- |
| [Lore Lookup](https://github.com/Ablation-Lab/claude-lore) | Makes Claude answer questions about Claude, Claude Code and the Claude apps from Anthropic's docs and release notes, with citations, instead of from memory. | Claude Code and the Claude app |
| [Cutproof](https://github.com/Ablation-Lab/video-review-tool) | Proofread a video without watching it. Lines up your narration with what's on screen and flags typos, numbers that don't match the voiceover, text shown too briefly to read, and audio problems, with timestamps. | Claude Code (Windows) |
| [Stowdeck](https://github.com/Ablation-Lab/stowdeck) | Gives Claude a skill and commands to list your running and recent Claude Code sessions and your snapshots, save a snapshot and open the Stowdeck app. | Claude Code (Windows) |
| [Seaready](https://github.com/Ablation-Lab/seaready) | Checks a plugin repository before you submit it to Anthropic's plugin directory, and drafts answers for the submission form. | Claude Code |
| [Tangent Jar](https://github.com/Ablation-Lab/tangent-jar) | Helps you stay on your main task during a focus session you start: Claude parks side questions in a parking list in your project, counts them against three tangent tokens per session, and nudges you back. | Claude Code |
| [Bench Diary](https://github.com/Ablation-Lab/bench-diary) | Keeps your research docs up to date while you work: once you turn it on in a conversation, Claude logs research notes, decisions, anecdotes and new experiment ideas into the right doc, and tells you in one line what it logged, with an undo. | Claude Code |
| [Langparity](https://github.com/Ablation-Lab/langparity) | Checks a translation against its source before you ship it: a local script finds missing parts, broken placeholders and formatting, changed numbers and untranslated text, then Claude reads every pair for meaning drift and tone and suggests corrected translations. | Claude Code |
| [Council Dial](https://github.com/Ablation-Lab/council-dial) | Runs a review council of Claude subagents the way you choose, and logs which way it ran and what it found, so you can compare council types over time. | Claude Code |

## Windows apps

| App | What it does | Platform |
| --- | --- | --- |
| [Stowdeck](https://github.com/Ablation-Lab/stowdeck) | Saves your whole set of Claude Code sessions as a snapshot and restores it in one click, shows your recent and running sessions, and has a tab for your other terminal windows. The Stowdeck plugin above lets Claude use it too. | Windows 11 |

Each repo's README has install steps, and explains exactly what the tool runs, reads and sends.

**Other repos:** [ablationlab-site](https://github.com/Ablation-Lab/ablationlab-site) (source for ablationlab.org) and [council-video](https://github.com/Ablation-Lab/council-video) (Remotion source for the Evolving Review Councils explainer video).

## Elsewhere

- Website: [ablationlab.org](https://ablationlab.org)
- YouTube: [@AblationLab](https://www.youtube.com/@AblationLab)

---

Code is MIT and docs are CC BY 4.0; please credit Ablation Lab.

Ablation Lab is independent and not affiliated with Anthropic.

Research by George, Ablation Lab.
