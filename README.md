# Peeps 👥

> *Your network is bigger than you think. Most of it is just invisible when you need it.*

**Peeps** is an open-source agent skill that turns the people you know into a private, searchable record — kept on your machine, owned by you.

No CRM. No app. No feed. Just files and your AI agent.

---

## What it does

- **Remembers people** — one markdown file per person, everything you know about them
- **Tracks organisations** — culture, size, Wikipedia link, and who you know there
- **Surfaces context** — "remind me what Leo does before my meeting tomorrow"
- **Finds connections** — "who do I know in fintech in Singapore?"
- **Drafts intros** — "connect Peter and Shaurya, they should meet"

```
peeps/
  leo-lau.md
  peter-boeckel.md
  shaurya-srivastava.md
  orgs/
    stripe.md
    steelcase.md
  ...
```

---

## Install

### Claude Code

```bash
mkdir -p ~/.claude/skills/peeps
curl -o ~/.claude/skills/peeps/SKILL.md https://raw.githubusercontent.com/Know-Your-People/peeps-skill/main/SKILL.md
```

### Other agents

```bash
npx skills add Know-Your-People/peeps-skill
```

Works with OpenClaw, Cursor, Codex, OpenCode, GitHub Copilot, and [40+ more agents](https://github.com/vercel-labs/skills#supported-agents).

### Hermes

```bash
hermes skills install peeps
```

---

## Then just talk to your peeps

```
"I just met someone called Leo at a design event."
"Who do I know in hardware supply chain?"
"Remind me to talk to Basel next week"
"Draft an intro between Peter and Shaurya."
"She just joined Stripe — note that and save what you know about Stripe's culture."
"Who in my network works at a VC fund?"
```

---

## Works best with

Peeps is part of a suite of personal intelligence skills:

- [**Haah** 🪩](https://github.com/Know-Your-People/haah-skill) — network dispatch. When your contacts don't have the answer, Haah asks your trusted circles — privately and consensually. When a query comes in from your circle, Peeps helps you answer it.
- [**Nooks** 📍](https://github.com/Know-Your-People/nooks-skill) — your saved places. When you're meeting someone, Nooks suggests the right spot based on your curated list of cafes, coworking spaces, and restaurants.
- [**Pages** 📖](https://github.com/Know-Your-People/pages-skill) — your reading life. When someone recommends a book, Peeps links it to their file. When both of you have read the same book, your agent surfaces it as a connection point.
- [**Vibes** 🎧](https://github.com/Know-Your-People/vibes-skill) — your cultural context. When you share a show, album, or podcast with someone, Peeps notes the shared taste and can surface it when drafting an intro or reconnecting.
- [**Digs** 🔭](https://github.com/Know-Your-People/digs-skill) — your active research threads. When someone in your network has expertise matching an open dig, Peeps flags them as a potential source.

Install all six and your agent knows your people, your places, your reads, your culture, and your open questions.

---

## Contributing

This is open source. Found a bug, want a feature, think the SKILL.md could be smarter? PRs welcome.

The skill lives in `SKILL.md`. That's the brain. Edit it, improve it, make it yours.

---

## License

MIT. Take it, fork it, build on it.

---

*Designed by Ilya Belikin @ Haah Inc*