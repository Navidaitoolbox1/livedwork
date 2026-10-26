# LivedWork

**Turn lived experience into a body of work.**

A free skill for Claude and ChatGPT that helps you find what only you can say, capture it every day, and turn it into content and a first small product.

By [Navid Taheri](https://navidaitoolbox.com) · Navid AI Toolbox

---

## Why this exists

Machines now learn faster than we do and know more than any of us. Anything that depends only on knowledge or technical expertise is getting cheaper every month.

What stays valuable is what a model cannot generate for someone else:

- **Lived experience**: what happened to you, and what you learned from it
- **Soft skills**: teaching, negotiating, listening, building trust
- **Judgment**: choosing what matters and what to leave out
- **A visible point of view**: the way your experiences connect

Most people have all four and can't see them, because they were never written down. LivedWork uses AI as an interviewer and organiser, not as a ghostwriter, to make them visible.

Read the full thinking behind it: [Why lived experience is the last advantage](docs/why-lived-experience.md)

## What's inside

| Module | What you get |
|---|---|
| **1. Idea Museum** | A five-minute daily capture habit and four "rooms" for sorting ideas: Loved, Proven, Lived, Questions |
| **2. Signature Interview** | Seven questions, asked one at a time, that end in your written **Thinking Signature** and 3 to 5 content pillars anchored in your own life |
| **3. 30-Day Sprint and First Product** | A week-by-week plan from first post to a first small paid product, using the **Signal + Solved** rule |

Plus three templates you can paste into Notes, Notion or a notebook: Idea Museum, Thinking Signature, and a 30-day tracker.

### See it in action

**Idea Museum**

![Idea Museum demo](docs/media/livedwork-1-idea-museum.gif)

**Signature Interview**

![Signature Interview demo](docs/media/livedwork-2-signature-interview.gif)

**30-Day Sprint and First Product**

![30-Day Sprint demo](docs/media/livedwork-3-sprint-first-product.gif)

## Install

### Claude (claude.ai, Claude desktop, Claude Code)

**Option A: as a Skill**
1. Download this repository as a ZIP, or download only the `skills/livedwork` folder.
2. Zip the `livedwork` folder.
3. In Claude, go to **Settings → Capabilities → Skills** and upload the ZIP.
4. Start a chat and say: *"Use LivedWork. Start the Signature Interview."*

**Option B: Claude Code**
```bash
git clone https://github.com/Navidaitoolbox1/livedwork.git
mkdir -p ~/.claude/skills
cp -r livedwork/skills/livedwork ~/.claude/skills/
```

**Option C: as a Project**
Create a Project, paste the content of `skills/livedwork/SKILL.md` into the project instructions, and upload the files in `references/` and `templates/` as project knowledge.

### ChatGPT

**Custom GPT**
1. Go to **Explore GPTs → Create → Configure**.
2. Paste `chatgpt/custom-gpt-instructions.md` into **Instructions**.
3. Upload every file from `skills/livedwork/references/` and `skills/livedwork/templates/` under **Knowledge**.
4. Name it LivedWork and start with: *"Start the Signature Interview."*

**ChatGPT Project**
Create a Project, paste the same instructions into project instructions, and add the same files.

### Codex and other agents

Copy `skills/livedwork` into `~/.agents/skills/` (or your agent's skills folder) and restart.

## How to use it

Start here if you're new:

1. **Signature Interview** (20 to 30 minutes). Answer honestly and with real moments. You'll get your Thinking Signature.
2. **Idea Museum** (5 minutes a day). Capture before ideas disappear.
3. **30-Day Sprint**. Publish, listen, and turn the most repeated question into your first product.

Good prompts to begin:

- *"Use LivedWork. Interview me. I'm a [your role] who [one line about your life]."*
- *"Here are 15 raw ideas from my notes. Sort them into my Idea Museum."*
- *"I have 4 hours a week and zero followers. Build my 30-day sprint."*
- *"People keep asking me how I [X]. Help me design a first product with Signal + Solved."*

## Principles

- AI asks, you answer. The key sentences stay yours.
- Specific beats impressive.
- Nothing is invented: no fake results, clients or quotes.
- Disagreement is where your signature lives.
- Start small, ship, listen, repeat.

## Roadmap

This repository is the free, open version. A LivedWork app is planned with features that need memory, data and automation. See [ROADMAP.md](ROADMAP.md).

## Credits

The influencer, personal brand and craftsman framing and the "idea museum" concept are adapted from **Dan Koe**'s essay on building a body of work. LivedWork adds the focus on lived experience and soft skills, the Signature Interview, and the Signal + Solved rule.

## License

Content and prompts: [CC BY-NC 4.0](LICENSE). Free to use, share and adapt for non-commercial purposes with credit to Navid Taheri / Navid AI Toolbox. For commercial use, get in touch via [navidaitoolbox.com](https://navidaitoolbox.com).
