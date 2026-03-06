# Insurance Risk & Cost Prediction
### Stop guessing. Start pricing right.

Insurers lose millions annually to mispriced policies, charging too little for high-risk customers, and losing low-risk ones to competitors. This project builds predictive models that explain what drives insurance costs and how to anticipate them.

---

## Dataset

The analysis uses the publicly available Medical Cost Personal Dataset (1,338 individuals), commonly used for insurance pricing analysis.
---

## The Core Finding

**Smoking doesn't just add a flat cost, but it a ctually changes how every other factor behaves.**

A smoker with high BMI doesn't pay more for two separate reasons. The combination compounds. Same with age : the older a smoker gets, the faster their costs grow compared to a non-smoker. Once that interaction was modelled properly, the accuracy jumped from **75% to 94%**.

The final model explains **94% of insurance cost variability** across 1,338 individuals.

<img width="1174" height="811" alt="image" src="https://github.com/user-attachments/assets/ff170396-9223-4ef6-b8d6-581660d3bb53" />


---

## What drives your insurance bill

| Factor | Impact |
|---|---|
| Being a smoker | +$23822 vs. a non-smoker |
| +1 unit of BMI | +$322 |
| +1 year of age | +$258 |
| Having children | +$993 vs. having none |
| Region / Gender | Minimal ~ dropped from the final model |

> Smoking also amplifies the effect of BMI, age, sex, and children. It's not just a variable, it's a **multiplier**.

---

## Model Progression

| Version | R² | What changed |
|---|---|---|
| Base regression | 0.75 | Age, BMI, smoker, children |
| + Interaction terms | **0.94** | Smoking modelled as a moderator across all variables |

The jump came from one insight: stop treating smoking as a yes/no flag and start asking how it reshapes every other relationship in the data.

