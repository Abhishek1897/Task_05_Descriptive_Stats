
# Task_05_Descriptive_Stats

This repository is part of **Research Task 5** for the course project on *Descriptive Statistics and Large Language Models*. The objective of this task is to explore how well a large language model (LLM) such as ChatGPT can answer complex, natural language questions about a small public dataset.

## 📊 Dataset

The dataset used is from the **Syracuse University Women’s Lacrosse team**, based on their 2020 season. It includes:

- `player_stats.csv` – individual player statistics
- `team_stats.csv` – aggregated team and opponent stats
- `period_stats.csv` – breakdown of stats by period
- `game_schedule.csv` – season schedule and game outcomes (note: some formatting issues were encountered)

## 🧠 Prompts and Responses

A set of natural language prompts were crafted to evaluate the LLM's ability to:

- Assess offensive vs defensive strategy
- Identify well-rounded players
- Rank players by scoring efficiency
- Analyze win outcomes based on scoring
- Determine clutch performance (game-winning goals)
- Find defensive specialists

Each prompt and its validated answer is recorded in `llm.md`.

## ✅ Deliverables

- `llm.md`: A markdown file listing each prompt and its corresponding answer with reasoning, metrics, and player analysis.
- CSV files: Raw data used to generate insights.
- (Optional) Python scripts for preprocessing and metric calculations.

## 📌 Notes

- For one of the prompts (Prompt 4), we encountered malformed score data (e.g., "21-Jun") that prevented reliable win-rate analysis. This failure was documented as part of the assignment instructions.
- Metrics such as Points, Defensive Contribution, and Pts/TO ratio were defined and used to guide LLM answers.


> This task demonstrates how LLMs can engage with structured data when guided by human-designed prompts and custom metrics.
