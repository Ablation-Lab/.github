# Ablation Lab

Open research into how AI agents work and review each other, and where they fall short, plus the tools built along the way.

## Research

**[Evolving Review Councils](https://github.com/Ablation-Lab/evolving-review-councils)**

Do councils of AI reviewer agents beat one agent at the same cost, and can they evolve to get better? Plan, pilot notes and open questions, all published as the work happens.

**[Human in the Loop](https://github.com/Ablation-Lab/human-in-the-loop)**

When AI agents can talk to each other directly, what does keeping a human in the middle actually buy you? The plan, with the hypotheses and how results are measured, is published in the repo.

**[Research Framework](https://github.com/Ablation-Lab/research-framework)**

A lightweight template for keeping a research project on one core question: every new idea is either linked back to it or parked, with a research map, an evidence log and a claims ledger.

## Claude plugins and skills

| Tool | What it does | Type | Platform |
| --- | --- | --- | --- |
| [Lore Lookup](https://github.com/Ablation-Lab/claude-lore) | When you ask about Claude, Claude Code or the Claude apps, it has Claude look up the answer in Anthropic's online docs, help pages and release notes and reply with links to the pages it used, instead of answering from memory. If something can't be confirmed there, Claude says so. | Plugin (skill) | Claude Code and the Claude app |
| [Cutproof](https://github.com/Ablation-Lab/video-review-tool) | Turns a rendered video or a Remotion project into a review pack Claude can check without watching it: frames at every scene change and every 2 seconds, the on-screen text, and your narration (from your script or subtitles) lined up with where it plays. It flags typos, numbers that don't match the voiceover, text shown too briefly to read, and audio problems (it measures loudness and flags clipping, clicks and long silences). Each finding comes with its timestamp in the video. | Plugin (skill) | Claude Code (Windows) |
| [Stowdeck](https://github.com/Ablation-Lab/stowdeck) | Gives Claude a skill and commands to list your running and recent Claude Code sessions and saved snapshots, save a snapshot and open the Stowdeck app. Needs the Stowdeck Windows app. | Plugin (skill + commands) | Claude Code (Windows) |
| [Seaready](https://github.com/Ablation-Lab/seaready) | Checks a plugin repo before you submit it to Anthropic's plugin directory, to catch many of the problems the portal would block or hold it for: plugin names already taken, identifiers that look like credentials, line-ending rules that stop validation, files written, registry changes or network requests the README doesn't mention, chat-history reads, hidden Unicode, and personal emails in the git history. It then drafts your answers for the submission form. | Plugin (skill) | Claude Code |
| [Tangent Jar](https://github.com/Ablation-Lab/tangent-jar) | Helps you stay on your main task in a Claude Code focus session you start. Tell Claude your main task, and when a side question comes up it parks it in a list in your project for later (asking first unless you said "park this") and nudges you back. You get three tangent tokens per session; after that Claude still parks each tangent, with some playful pushback. | Plugin (skill) | Claude Code |
| [Bench Diary](https://github.com/Ablation-Lab/bench-diary) | Keeps your research notes up to date as you work in Claude Code. Turn it on in a conversation, and Claude logs the notes, decisions, anecdotes and experiment ideas you mention into the right Markdown doc in your project, from the docs you choose, without asking first. Each time, it tells you in one line what it logged, with an undo, and it leaves out secrets and personal details. | Plugin (skill) | Claude Code |
| [Langparity](https://github.com/Ablation-Lab/langparity) | Checks translations of your app or docs against their source; it doesn't translate for you. A local script compares each translated file with its source (JSON, Flutter ARB, gettext .po, Java .properties, Apple .strings, Android strings.xml, XLIFF, and Markdown or plain text) and flags missing or added text, broken placeholders and formatting, changed numbers, and text left untranslated. Claude then reads each pair for meaning and tone, such as a formal or informal "you", and suggests a corrected translation for each problem it confirms. | Plugin (skill) | Claude Code |
| [Council Dial](https://github.com/Ablation-Lab/council-dial) | When you want code, docs or a plan reviewed, Council Dial has Claude run a review council of subagents set up the way you choose: specialised or generalist reviewers, a judge, a pooled list or a majority consensus to combine their findings, and optional debate, sequential and single-reviewer baseline runs. Claude tells you how many subagents a run will use and waits for your yes. Each run's type and results go into a log in your project, so you can compare council types over time. | Plugin (skill) | Claude Code |

## Windows apps

| App | What it does | Type | Platform |
| --- | --- | --- | --- |
| [Stowdeck](https://github.com/Ablation-Lab/stowdeck) | A Windows app for your Claude Code sessions: see what's running now and what you worked on in the last 24 hours, 3, 7 or 30 days, save your whole set of sessions as a snapshot and reopen them in one click, each resuming its conversation, and start new sessions. A Terminals tab lists your other terminal windows, such as other CLI agents and dev servers, so they can go in a snapshot too. You can also name sessions and open a project's folder, editor or GitHub page from its row. | Desktop app | Windows 11 |

Each repo's README has install steps, and explains exactly what the tool runs, reads and sends.

**Other repos:** [ablationlab-site](https://github.com/Ablation-Lab/ablationlab-site) (source for ablationlab.org) and [council-video](https://github.com/Ablation-Lab/council-video) (Remotion source for the Evolving Review Councils explainer video).

## Elsewhere

- Website: [ablationlab.org](https://ablationlab.org)
- YouTube: [@AblationLab](https://www.youtube.com/@AblationLab)

---

Code is MIT and docs are CC BY 4.0; please credit Ablation Lab.

Ablation Lab is independent and not affiliated with Anthropic.

Research by George, Ablation Lab.
