# Master Agent AI

**Data-driven graduate admission tools. Replacing consultants with algorithms.**

## QuantPath

MFE admission prediction engine — GPBoost model (AUC 0.723) on 13,100+ records across 15 focused programs.

| Capability | Description |
|-----------|-------------|
| **Admission Prediction** | GPBoost model with per-program random intercepts and bias correction |
| **Profile Scoring** | 5-dimension evaluation across 37 sub-factors |
| **School Ranking** | Reach/target/safety with P(admit) confidence intervals |
| **Prerequisite Matching** | Course-by-course comparison against program requirements |

### Quick Start

```bash
git clone https://github.com/MasterAgentAI/QuantPath.git
cd QuantPath && pip install -e .
quantpath predict  # interactive mode — answer 8 questions, get results
```

### Tech

Python · GPBoost · LightGBM · scikit-learn · 465 tests · GitHub Actions CI

---

**Built by [Ethan Yang](https://github.com/YichengYang0405)** — UIUC CS+Econ+Stats, Quantitative Researcher at Square Kettle LLC.
