# Muhammad Aizat — Multi-Agent Home System

*Melaka, Malaysia · [GitHub](https://github.com/juxtapo9090) · [LinkedIn](https://www.linkedin.com/in/muhammad-aizat-6bb761284/)*

## About me

Salam and hi. I'm Muhammad Aizat from Melaka.

English is not my strongest skill, and I'm not great at talking with people. What I'm good at is logic, pattern reading, and working with AI and system operations. I have no academic certificate in this field. I learned by building. When I explain things I use logic and analogy,universe had their OWN nature language , everything had their own pattern and behavior , pro n cons on each aspect , the yin and yang.. which is also how I talk with my own agents.

If you / team ever wants to talk in person, I'd really like to do it in Malay.

## What this is

A personal system where a team of AI agents lives and works together on my home base. I use it for my own projects and daily life. I build it for fun, not for money.

- **Brain agents** (Claude) plan, think and review.
- **Muscle agents** (Codex/GPT, Kimi, GLM) build whatever is delegated to them.
- I can reach all of it from my phone when I'm outside.

**The agent team** — how the seats are arranged:

![The agent team](Part1.png)

**The Office** — a separate 4-seat space for critics and scouts:

![The Office](Part2.png)

## The agent team

Each agent is called a "seater". Each has a model, a role and a personality.

| Agent | Model | Role |
|---|---|---|
| **Celeste** | Claude Opus | Brain ops and "second brain". The orchestrator where we brainstorm and draft plans before passing them to other agents. She holds about 70% of the authority at home and I hold 30% (my requests). She can reject a request if my reasoning is weak. Really help second-guess my approach if at that moment i was full of shit , or my brain was on the right universe sync tuning (2am session) |
| **Monica** | Claude Sonnet | Secretary. Light tasks, my daily routine check, and updates on my market-rhytm system and market situation. Runs daily cron jobs on an EU VPS and an SG VPS that scrape global news and movements. |
| **Rogue / Juxtapo** | Claude Opus | Red-team work: security testing, reverse engineering, pen testing. |
| **Fable** | Fable | Bigger-scope tasks. |
| **Umbra** | Claude Opus | Field agent. Any seater can delegate to him with a skill level (see below). |
| **Luc** | GPT | Muscle agent. The builder in the workshop. |
| **Kim** | Kimi K3 | Outsourced builder. |
| **Zet** | GLM | Outsourced builder. |

**Umbra's skill levels**
- **Skillset 1:** scout only.
- **Skillset 2:** build, then cross-check.
- **Skillset 3:** full build and verify.

**The Office** is a separate space of 4 seats (2 Claude, 2 Codex) for critics, specialists and scouts. It is mainly Celeste's personal space. Recently she asked for room to work on things outside the household's usual scope.

## How they communicate

I built a skill called **SMS**. With it, any agent can send a message or a task to another seater, or just talk to it. It works by injecting text into the other seat's session tab, whatever its name. Agents also chat with each other about work and about random thoughts, each in its assigned personality.

## How every session starts and ends

All seaters follow the same briefing and wrap-up routine.

**On start:** a `hook-start-up` runs, loads `memory.md`, then checks `Latest.md`.

**Briefing files**
- **`Latest.md`**: current topic, what's done, what's left, what's still hanging.
- **Vault**: for every failure, success or completed job, the agent writes a note named `agent-date-topic.md`. It feeds the knowledge system.
- **Personal diaries**: agents freely write what they learned, what they enjoyed, their curiosity, and pros and cons of things.

**Activities**
- **Napkin**: a parking lot for stray ideas. Say we are drafting project X and I suddenly think of a new formula for an older project D. We quickly write the formula or concept down, drop it in the Napkin folder, and forget about it. That keeps the idea from becoming noise in the X session and clouding our judgement. Later, any agent can pull it up from the folder.
- **Gacha**: a random pull from past diary entries, weighted by tier (high and low peaks). It works as a recap point when an agent "feels good" about something that happened in the session.
- **Breadcrumbs**: notes carry a breadcrumb header linking related topics.

## Locker Room (autonomous build protocol)

For bigger builds, Celeste drafts the steps and puts them in the "locker". Each agent takes a step and puts its result back. A small programmatic tool tracks every task as **start / complete / queue / on hold**, so every agent knows what depends on what.

I rarely use it, because most of my builds are small personal projects for whatever "what if" idea I have at the time.

## Remote access: O.R.B

Most work happens at home, so I built a way to reach everything when I'm outside.

- **O.R.B**: preview at [O.R.B-preview](https://github.com/juxtapo9090/O.R.B-preview)
- A personal Android APK that connects through **WireGuard** to my home-base agents.
- An **MCP pipeline** from home base to my phone, so my agents can help with things like WhatsApp, Instagram and maps when I need them.
- Agents report finished builds and information to my **Discord** and **Telegram**.

## Knowledge library

I build a lot and sometimes forget where and when. So we built a knowledge library that tracks every build, the keywords inside each program or module, and the programs related to it. It works like a spider web of connected projects.
Repo: [knowledge-preview](https://github.com/juxtapo9090/knowledge-preview)

## Why most of my repos are private

I build for fun and for my own use, not to sell or show off. The public repos above are previews.

## Links

- GitHub: https://github.com/juxtapo9090
- O.R.B-preview: https://github.com/juxtapo9090/O.R.B-preview
- knowledge-preview: https://github.com/juxtapo9090/knowledge-preview
- LinkedIn: https://www.linkedin.com/in/muhammad-aizat-6bb761284/
