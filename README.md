# 🧞 Literal Genie: AI Wrangler

A game that teaches the **art of prompting** — with 100 real-world challenges. Pick the best prompt, spot the hallucination, fix the follow-up, and learn why the right words matter.

**Play it live:** https://syedyousafraza.github.io/literal-genie-ai-wrangler/

## The idea

Coding isn't the skill anymore — *telling the AI exactly what you mean* is. Every question is a real situation — a boss who needs a summary, a crashing Python script, a job interview, a business pitch, a birthday post — where a weak prompt gets a bad result and a good prompt gets a great one. Bloop, the literal robot, reacts to every answer. And after every question, the game explains **why** the best prompt wins.

## The 100-question bank

10 categories × 10 challenges, in random order, endless play (the bank reshuffles when you finish it):

| Category | What you'll learn |
|---|---|
| Work Email | Audience, length, structure — and what an apology actually needs |
| Coding | Bug reports, examples that pass AND fail, roles for reviewers |
| Data | Ask a question before you analyze; check the claim against the numbers |
| Marketing | Audience + tone + constraints; examples beat adjectives |
| Career | CVs need numbers; interviews need STAR, not essays |
| Learning | Level + analogy + quiz; practice needs correction |
| Business | Context + format; "no source, no number" |
| Everyday | Real constraints (budget, dates, equipment) make plans usable |
| Creative | Prompts are recipes: length, genre, setting, twist, tone |
| AI Safety | Hallucinations, fake sources, bias, and keeping your data private |

## 4 challenge types

| Type | The skill |
|---|---|
| 🎯 Pick the best prompt | Choose the prompt a pro would actually send |
| 🧩 What's missing? | Spot the ONE ingredient that fixes a weak prompt |
| 🕵️ Spot the hallucination | AI lies confidently — catch the fake fact |
| 🔧 Fix the follow-up | The AI messed up. What do you say next? |

## See it working

Bloop, mid-game on a hallucination challenge:

![Literal Genie gameplay](docs/screenshots/gameplay.png)

## Features

- **100 verified challenges** — every question machine-checked (answer in range, no duplicates, correct answers spread across all positions so you can't guess by position)
- **Wrong answers are close calls** — each one is a real prompting mistake (vague, missing one ingredient, fixing the wrong thing). Hallucination checks hide in small detail changes: one week vs two weeks, $49 vs $79, a real section number with a fake claim attached.
- **A "Why" lesson after every question** — the learning payload, in plain words
- **Endless random play** — shuffled order, bank reshuffles when complete
- **Hearts, streaks and a 30-second timer** — 3 hearts, streak bonuses, speed bonuses, confetti on streaks and new best scores
- **Best score saved** on your device (localStorage)
- Bloop the robot, with expressions that change: thinking, confused, smug, happy, worried
- Sound effects (with mute) and a shareable score for LinkedIn

## Run it yourself

No build step, no dependencies — just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server
# then open http://localhost:8000
```

## License

MIT
