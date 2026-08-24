## Hey, I'm Vignesh 👋

Senior Data Scientist → AI builder. I use LLMs to ship tools I actually want to exist — and I **measure** whether they actually work.
Working at the intersection of **AI · evals · finance · product**.

---

### 🔬 Currently in the weeds: agent evals

**[agent-skill-lift](https://github.com/Vbdata13/agent-skill-lift)** — I wrote 14 skills for an autonomous coding agent and measured the *lift* each one gives, paired per task, on the [BenchFlow SkillsBench](https://github.com/benchflow-ai/skillsbench) benchmark.

- **`lift = score(agent + my skills) − score(agent alone)`**, scored on a **held-out** task set — so skills have to generalize, overfitting is banned
- Confirmed lifts up to **+1.00** (PowerPoint DrawingML, strict-verified Excel, geospatial distance)
- Findings that survived the data: skill **discovery is selective** (only the domain-matching skill ever fires, even against a negative control), and **binary graders hide real improvement** — the honest signal is the per-metric delta
- Full methodology, harness gotchas, and the dead ends are written up in [`NOTES.md`](https://github.com/Vbdata13/agent-skill-lift/blob/main/NOTES.md)

> If a skill doesn't move the number, it doesn't ship.

---

### 🛠️ Also building

| Project | What it does | Stack |
|---|---|---|
| 📊 **[Option Screener](https://github.com/Vbdata13/option-screener)** | Automated Robinhood options screener — filters POP ≥ 65%, composite scoring, portfolio-constraint optimization | Python · Streamlit · robin_stocks |
| 🎮 **[AI Browser Games](https://github.com/Vbdata13/games)** | Clue Craft (daily AI crossword, 3 difficulty tiers) + Daily Discovery (element-combination puzzle) | Vanilla JS · Claude API · Vercel |

---

**Stack I reach for:** Python · JavaScript · Claude API · eval harnesses (`uv`/pytest) · Streamlit · Vercel
**Day job:** Product Analytics + AI @ Meta
**Community:** Reviewer, ICML 2026
**Currently obsessed with:** agent skills, eval design, and making *"it works"* mean something you can measure.
