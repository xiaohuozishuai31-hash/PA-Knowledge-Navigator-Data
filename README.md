# PA Knowledge Navigation System — Evaluation Dataset

This repository provides an evaluation dataset for a knowledge navigation system in Computer Organization PA (Programming Assignment) experiments, including test questions, reference answers, scoring results, and prompt templates.


## 📁 Repository Structure
PA-Knowledge-Navigator-Data/
├── README.md
├── Problems_Collection.json # Test questions with reference answers
├── Horizontal_comparison_score.json # System comparison scoring results
├── Confidence_score_statistics.json # Confidence statistics results
├── prompts.txt # Prompt templates


## 📄 File Descriptions

### Problems_Collection.json
20 test questions across 4 categories (Concept Explanation, Debugging Guidance, Causal Reasoning, Procedure Query), 5 questions per category, each with a reference answer.

### Horizontal_comparison_score.json
Scoring results of three systems on the 20 questions on a 1–3 scale (3 = correct/complete, 2 = partially correct, 1 = incorrect).

### Confidence_score_statistics.json
Confidence score distribution across the 20 questions, broken down by confidence level (High/Medium/Low).

### prompts.txt
System prompt and evaluation prompt templates.

## 🔬 Usage

You may directly use the 20 questions from `Problems_Collection.json` as a test set, apply the same scoring rubric for evaluation, and compare your results against the scores in this repository.


---

*Last updated: September 2026*
