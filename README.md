# InnovatorBench Agent Behavioral Analysis Reports

Behavioral analysis of **596 agent trajectories** across InnovatorBench Task 1–20.

🌐 **Live site:** https://lyumanshanye.github.io/agent-eval-reports/

## Views

| View | Link | Runs per task | Purpose |
|---|---|---|---|
| **Top 10 (default)** | [`index.html`](./index.html) | Top 10 by score | Quick comparison — only the best runs |
| **Full archive** | [`full/`](./full/) | All 25–36 per task | Complete data — every run |

## What's in each report

Each per-task HTML covers the runs for that task and breaks them down across 34+ trajectory metrics:

- **Leaderboard** — runs ranked by eval score (with Accuracy / Entropy / Aux metrics)
- **Model-family grouping** — side-by-side comparison across Claude / GPT / GLM / Kimi families
- **Action timelines** — color-coded per-step visualization of every run
- **Metric cards** — Best/Worst evidence + full table for each behavioral metric
- **Success vs failure patterns** — what distinguishes scored runs from zero-score / no-eval runs
- **Conclusions** — most discriminative metrics + score correlations

## Files (top-10 view)

| File | Task |
|---|---|
| [`index.html`](./index.html) | Overview + navigation |
| [`Task1_Behavioral_Analysis.html`](./Task1_Behavioral_Analysis.html) | Task 1 |
| [`Task2_Behavioral_Analysis.html`](./Task2_Behavioral_Analysis.html) | Task 2 |
| ... | ... |
| [`Task14_Behavioral_Analysis.html`](./Task14_Behavioral_Analysis.html) | Task 14 (GRPO entropy collapse) |
| ... | ... |
| [`Task20_Behavioral_Analysis.html`](./Task20_Behavioral_Analysis.html) | Task 20 |

Full 25–36-run archive: [`full/`](./full/)
