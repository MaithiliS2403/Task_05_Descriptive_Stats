# Task_05_Descriptive_Stats
# Task 05 – Descriptive Statistics & LLMs

This project explores how large language models (LLMs) like ChatGPT interpret and answer natural language questions based on structured sports data. The dataset used contains the 2025 Syracuse Women’s Lacrosse season results and team statistics.

---

## 📊 Dataset

- **Source**: Syracuse University Women’s Lacrosse public stats PDF
- **Note**: Dataset is summarized in `dataset_summary.md` (do not upload raw PDF)

---

## 📁 Files in This Repo

| File                | Description                                         |
|---------------------|-----------------------------------------------------|
| `dataset_summary.md`| Game log and team stats extracted from PDF          |
| `prompt_log.md`     | Natural language prompts and LLM responses          |
| `README.md`         | Project overview and instructions                   |

---

## 💡 Project Goals

- Use LLMs to answer factual and strategic questions from sports data
- Compare LLM responses to known stats (manual fact-checking)
- Experiment with prompts to improve LLM reasoning and accuracy

---

## 🧠 Sample Questions Asked

- How many games did SU play and win?
- Was SU stronger in the first or second half?
- Should a coach focus more on offense or defense to gain wins?

---

## 📨 Submission

Submitted to: `jrstrome@syr.edu`  
Progress reported via [Qualtrics OPT Form](https://syracuseuniversity.qualtrics.com/jfe/form/SV_cDgnzM695AMx8d8)

---

## 🔄 Research Expansion

As part of extending Task 05, the following additional components were added:

✅ LLM Comparison
A structured comparison between ChatGPT and Claude was conducted using the same set of prompts. Their answers were evaluated for accuracy, depth, and reasoning style. Claude tended to offer more strategic insights, while ChatGPT was stronger with raw numeric analysis.

- See: [`llm_comparison.md`](./llm_comparison.md)

✅ Strategic Coaching Prompts
New prompts were introduced, asking LLMs to think like a coach and make recommendations on how Syracuse could improve future performance. This tested the model’s ability to reason beyond data and simulate decision-making.

- Example: “Should a coach focus on offense or defense to win two more games next season?”
- See: Additional entries in [`prompt_log.md`](./prompt_log.md)
