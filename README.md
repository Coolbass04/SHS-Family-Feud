# SHS Department Game: Family Feud Style

Welcome to the SHS Department Game Show Documentation!  
This repository makes it easy for anyone on the team to run our *Friendly Feud*–style department bonding game using the open-source platform [Friendly Feud](https://www.famf.app/docs/en/help).

Whether you're hosting, moderating, or supporting behind the scenes, these guides explain everything you need to know — clearly, simply, and without needing prior experience.

---

## 🧭 Overview

- **Game Format:** Based on *Family Feud*, using the web tool [Friendly Feud](https://www.famf.app).  
- **Rounds:** Six normal questions plus one optional Bonus Round. Depending on time, play 3–6 questions.  
- **Teams:** Four teams total. Steals occur when the main team reaches three X’s — other teams each write down one answer; if any is correct, that team steals the points. If none are correct, the playing team keeps their points.  
- **Roles:**
  - [Host](./docs/HOST_INSTRUCTIONS.md) – Leads the game, manages buzzers, reveals answers, and keeps the energy going.  
  - [Moderator](./docs/MODERATOR.md) – Tracks time, monitors buzz-ins, judges answers, and helps with scoring fairness.  
  - [Sara / Scorekeeper](./docs/GAME_OVERVIEW.md#-at-a-glance) – Tallies and announces total points each round.

---

## 📂 Files Included

| File | Purpose |
|------|----------|
| [`docs/GAME_OVERVIEW.md`](./docs/GAME_OVERVIEW.md) | Full explanation of the game structure, roles, and terminology |
| [`docs/HOST_INSTRUCTIONS.md`](./docs/HOST_INSTRUCTIONS.md) | Complete step-by-step guide for the host |
| [`docs/MODERATOR.md`](./docs/MODERATOR.md) | Timing, pacing, and fairness guide |
| [`docs/QUESTION_ANSWER_REFERENCE.md`](./docs/QUESTION_ANSWER_REFERENCE.md) | All normal and bonus round questions with point values |
| [`game/shs_game.csv`](./game/shs_game.csv) | Upload-ready CSV for Friendly Feud |
| [`game/FamilyFeudSHS.json`](./game/FamilyFeudSHS.json) | JSON version for Friendly Feud |
| [`docs/README.md`](./docs/README.md) | Quick guide for this folder |

---

## 🖥️ Tech Setup

- Use **one laptop connected to a TV or projector** to display the game.  
- The Host runs the [Friendly Feud website](https://www.famf.app) and controls the board.  
- Use **egg buzzers** for the initial question buzz-ins.  
- The Moderator tracks timing and manages judgment calls.  
- Print the `QUESTION_ANSWER_REFERENCE.md` as a manual backup sheet if needed.

---

## 🧾 Scoring & Rounds

- Each answer is worth points based on real SHS survey results (scaled to total ~100 per question).  
- After each round, **Sara tallies the totals** and announces which team is leading.  
- The **Bonus Round** uses five rapid-fire questions — duplicates aren’t allowed, and timing is strict (20 seconds per player).

---

## 💡 Getting Started

1. Review [`GAME_OVERVIEW.md`](./docs/GAME_OVERVIEW.md) for a quick understanding of how everything fits together.  
2. Hosts should read [`HOST_INSTRUCTIONS.md`](./docs/HOST_INSTRUCTIONS.md).  
3. Moderators should review [`MODERATOR.md`](./docs/MODERATOR.md).  
4. Import `shs_game.csv` or `FamilyFeudSHS.json` into [Friendly Feud](https://www.famf.app/new).  

When in doubt, the Moderator and Host can check the `QUESTION_ANSWER_REFERENCE.md` to confirm answers and point values.

---

## 🎉 Goal

This game is designed to bring the SHS department together — to laugh, connect, and celebrate teamwork in a fun, supportive way.

Let the feud begin!
