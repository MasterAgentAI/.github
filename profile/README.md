# Master Agent AI

**Data-driven graduate admission tools. Replacing consultants with algorithms.**

## QuantPath

Our flagship project — an MFE admission prediction engine with 12,800+ records, 34 programs, and a GPBoost mixed-effects model.

| Capability | Description |
|-----------|-------------|
| **Admission Prediction** | GPBoost model (AUC 0.716) with per-program random intercepts and bias correction |
| **Profile Scoring** | 5-dimension evaluation across 37 sub-factors (Math, Stats, CS, Finance, GPA) |
| **School Ranking** | Reach/target/safety classification with P(admit) confidence intervals |
| **Prerequisite Matching** | Course-by-course comparison against 28 program requirements |
| **Gap Analysis** | Priority-ranked gaps with specific action recommendations |
| **Course Optimization** | 37 course categories including reinforcement learning |

### Data

| Dataset | Records |
|---------|---------|
| Admission records | 12,800+ (GradCafe, QuantNet, Reddit, 1point3acres) |
| LinkedIn alumni profiles | 930 (20 MFE programs, employer + undergrad data) |
| Program database | 28 (QuantNet 2026 rankings, prerequisites, salaries) |
| Trained models | GPBoost v2 (13 features) + LR v1 (21 per-program models) |

### Quick Start

```bash
git clone https://github.com/MasterAgentAI/QuantPath.git
cd QuantPath && pip install -e .
quantpath evaluate --profile examples/sample_profile.yaml
```

### Tech

Python · GPBoost · LightGBM · scikit-learn · 465 tests · GitHub Actions CI

---

**Built by [Ethan Yang](https://github.com/YichengYang0405)** — UIUC CS+Econ+Stats, Quantitative Researcher at Square Kettle LLC.
