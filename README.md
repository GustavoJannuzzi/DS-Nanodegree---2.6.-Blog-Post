# The AI Era: What 49,000 Developers Reveal About Trust, Fear, and Job Satisfaction

A Data Science analysis of the **Stack Overflow Developer Survey 2025** following the CRISP-DM process.

---

## Motivation

AI tools have become a defining feature of software development in 2025. This project investigates how developers
*really* feel about AI: Are they adopting it? Do they trust it? Do they fear it? And does any of this
actually predict whether a developer is happy at work?

**Four business questions drive the analysis:**

1. How widespread is AI tool adoption among developers in 2025?
2. Do developers trust the AI tools they use — and how does trust relate to job satisfaction?
3. Who fears AI will take their job? What profiles are most threatened?
4. Can we predict developer job satisfaction from their profile and AI-related attributes?

---

## Repository Contents

| File | Description |
|---|---|
| `stackoverflow_ai_analysis.ipynb` | Main Jupyter notebook — full CRISP-DM analysis, EDA, ML model, visualizations |
| `build_notebook.py` | Script used to generate the notebook JSON programmatically |
| `README.md` | This file |
| `stack-overflow-developer-survey-2025/` | Survey dataset (not tracked in git — download separately) |
| `fig_*.png` | Chart images exported from the notebook |

---

## Libraries Used

| Library | Version | Purpose |
|---|---|---|
| `pandas` | 2.x | Data loading, cleaning, transformation |
| `numpy` | 1.x | Numeric operations |
| `matplotlib` | 3.8 | Visualization |
| `seaborn` | 0.13 | Visualization styling |
| `scikit-learn` | 1.3 | Random Forest classifier, cross-validation, metrics |
| `nbconvert` | — | Notebook execution |

---

## Key Findings

| Question | Finding |
|---|---|
| AI Adoption | **78.5%** of developers use AI tools; **47.1%** use them daily |
| AI Trust | Only **32.7%** trust AI outputs — most use it anyway. #1 frustration: almost-right solutions |
| AI Threat | Only **15%** feel threatened. Front-end devs and juniors worry most. Daily users feel *more* threatened than non-users |
| Job Satisfaction | Experience (40.5% importance) dominates over AI-related factors (28.5%). Work flexibility matters more than AI enthusiasm |

**ML Model:** Random Forest with `class_weight='balanced'`
- Accuracy: **68.4%** | ROC-AUC: **0.584** | 5-Fold CV: **65.3% ± 1.7%**

---

## Dataset

**Stack Overflow Developer Survey 2025**
- Source: [survey.stackoverflow.co](https://survey.stackoverflow.co/)
- Respondents: 49,191 developers across 180+ countries
- Columns: 172 features covering technology usage, AI attitudes, career, compensation, and more

To reproduce the analysis, download the 2025 survey results and place the CSV at:
`stack-overflow-developer-survey-2025/survey_results_public.csv`

---

## Blog Post

Read the non-technical summary on Medium:  
[The AI Era: What 49,000 Developers Reveal About Trust, Fear, and Job Satisfaction](#)

*(link updated after publishing)*

---

## Acknowledgements

- Stack Overflow for making the annual developer survey publicly available
- The CRISP-DM framework for structured data science process guidance
- Udacity Data Science Nanodegree — Project 2.6
